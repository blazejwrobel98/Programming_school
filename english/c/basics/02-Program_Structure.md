# Struktura Programu w Języku C

Każdy program w języku C ma swoją specyficzną strukturę, która składa się z kilku kluczowych elementów. Zrozumienie tej struktury jest niezbędne do pisania programów.

## Podstawowa Struktura Programu
Program w C zwykle składa się z następujących części:
1. **Preprocesor Directives**: Linie, które zaczynają się od `#`, służą do dołączania plików nagłówkowych.
2. **Funkcja main()**: Każdy program w C musi zawierać funkcję `main()`, która jest punktem startowym programu.
3. **Deklaracje Zmiennych**: Miejsce, gdzie deklaruje się zmienne używane w programie.
4. **Ciało Funkcji**: Zawiera kod, który wykonuje operacje programu.

## Prosty Program: Hello World
Poniżej znajduje się przykład prostego programu w C, który wypisuje na ekranie "Hello, World!".

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
```

### Wyjaśnienie Kodu
- `#include <stdio.h>`: To jest dyrektywa preprocesora, która mówi kompilatorowi, aby dołączył standardową bibliotekę wejścia-wyjścia (standard input-output library). Umożliwia to używanie funkcji `printf`.
- `int main()`: Deklaracja głównej funkcji `main()`, która jest punktem startowym każdego programu w języku C. Słowo `int` przed `main` oznacza, że funkcja ta zwraca wartość typu całkowitego (integer).
- `printf("Hello, World!\n");`: Wywołanie funkcji `printf` powoduje wypisanie na ekranie tekstu podanego w nawiasach. Sekwencja `\n` na końcu jest znakiem nowej linii, co powoduje przejście kursora do nowego wiersza.
- `return 0;`: Zwraca wartość `0` z funkcji `main`, co w konwencji języka C oznacza, że program zakończył się pomyślnie.

## Kompilacja i Uruchomienie Programu
Aby uruchomić program napisany w C, musisz najpierw skompilować kod źródłowy do postaci pliku wykonywalnego. Używając systemu Linux, możesz to zrobić za pomocą kompilatora GCC:

```bash
gcc nazwa_pliku.c -o nazwa_programu
./nazwa_programu
```

Po skompilowaniu, użyj komendy `./nazwa_programu` aby uruchomić skompilowany program. Jeśli wszystko poszło dobrze, na ekranie powinien pojawić się napis "Hello, World!".

## Wnioski
Zrozumienie struktury programu w języku C oraz umiejętność kompilacji i uruchamiania prostego programu stanowią fundamenty programowania w C. Kiedy już opanujesz te podstawy, będziesz gotowy na eksplorowanie bardziej zaawansowanych aspektów języka w kolejnych rozdziałach tego kursu.

Nauka programowania wymaga praktyki, więc eksperymentuj z modyfikowaniem i uruchamianiem różnych przykładów kodu, aby lepiej zrozumieć, jak działają. Pamiętaj, że każdy kawałek kodu, nawet najprostszy, jest krokiem w kierunku stania się doświadczonym programistą.
