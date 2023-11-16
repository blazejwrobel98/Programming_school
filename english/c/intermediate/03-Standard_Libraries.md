
# Biblioteki Standardowe w Języku C

Biblioteki standardowe w języku C dostarczają zestawu gotowych funkcji, które pomagają w rozmaitych zadaniach programistycznych. W tym rozdziale omówimy niektóre z najważniejszych bibliotek standardowych w C.

## Biblioteka stdio.h
Biblioteka `stdio.h` zawiera funkcje do wejścia-wyjścia, takie jak `printf`, `scanf`, `fgets` i `fputs`.

### Przykłady Użycia
```c
#include <stdio.h>

int main() {
    char buffer[100];
    printf("Wpisz tekst: ");
    fgets(buffer, 100, stdin);
    printf("Wpisano: %s", buffer);
    return 0;
}
```

## Biblioteka stdlib.h
`stdlib.h` zawiera funkcje do zarządzania pamięcią, konwersji typów oraz innych użytecznych operacji.

### Przykłady Użycia
```c
#include <stdlib.h>

int main() {
    int *wsk = malloc(10 * sizeof(int)); // Alokacja pamięci
    free(wsk); // Zwalnianie pamięci
    return 0;
}
```

## Biblioteka string.h
`string.h` oferuje funkcje do manipulacji i porównywania łańcuchów znaków.

### Przykłady Użycia
```c
#include <string.h>

int main() {
    char str1[10] = "Hello";
    char str2[10] = "World";
    strcat(str1, str2); // Łączenie łańcuchów
    int len = strlen(str1); // Długość łańcucha
    return 0;
}
```

## Wnioski
Biblioteki standardowe w C są niezwykle użyteczne i stanowią podstawę wielu programów. Pozwalają na łatwe wykonanie wielu zadania, takich jak obsługa wejścia i wyjścia, zarządzanie pamięcią, czy operacje na łańcuchach znaków.
