
# Programowanie Wielowątkowe w Języku C

Programowanie wielowątkowe w C pozwala na równoczesne wykonywanie różnych części programu, co może znacząco zwiększyć wydajność i reaktywność aplikacji. W tym rozdziale skupimy się na podstawach tworzenia i zarządzania wątkami.

## Biblioteka pthreads
Do tworzenia wątków w C na platformach Unixowych używa się biblioteki `pthreads`. Jest to standardowa biblioteka do programowania wielowątkowego.

### Tworzenie Wątku
```c
#include <pthread.h>

void *funkcjaWatku(void *arg) {
    // Kod wykonywany przez wątek
    return NULL;
}

int main() {
    pthread_t watek;
    pthread_create(&watek, NULL, funkcjaWatku, NULL);
    pthread_join(watek, NULL); // Oczekiwanie na zakończenie wątku
    return 0;
}
```

## Zarządzanie Wątkami
Oprócz tworzenia wątków, ważne jest także ich odpowiednie zarządzanie, w tym synchronizacja za pomocą zamków (`mutex`).

### Mutex
Mutex (mutual exclusion) służy do zapewnienia wzajemnego wykluczenia, czyli dostępu do zasobu tylko przez jeden wątek na raz.

```c
pthread_mutex_t mutex = PTHREAD_MUTEX_INITIALIZER;

void *funkcjaWatku(void *arg) {
    pthread_mutex_lock(&mutex);
    // Kod wykonywany tylko przez jeden wątek na raz
    pthread_mutex_unlock(&mutex);
    return NULL;
}
```

## Wnioski
Programowanie wielowątkowe jest potężnym narzędziem, pozwalającym na lepsze wykorzystanie zasobów sprzętowych i zwiększenie wydajności aplikacji. Wymaga jednak ostrożności i dobrej znajomości mechanizmów synchronizacji, aby uniknąć problemów takich jak zakleszczenia (deadlocks) czy wyścigi (race conditions).
