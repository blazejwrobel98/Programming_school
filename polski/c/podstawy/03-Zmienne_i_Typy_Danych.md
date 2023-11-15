
# Zmienne i Typy Danych w Języku C

W programowaniu w języku C, zrozumienie zmiennych i typów danych jest niezbędne do tworzenia efektywnych i działających programów. W tym rozdziale przyjrzymy się podstawom zmiennych i typów danych w C.

## Co to są Zmienne?
Zmienna to nazwane miejsce w pamięci, które przechowuje dane. W języku C, zanim użyjemy zmiennej, musimy ją zadeklarować, określając jej typ, który definiuje, jaki rodzaj danych będzie przechowywać.

## Typy Danych
C wyróżnia kilka podstawowych typów danych:
- **int**: Służy do przechowywania liczb całkowitych.
- **float**: Do przechowywania liczb zmiennoprzecinkowych (czyli z częścią dziesiętną).
- **char**: Przechowuje pojedyncze znaki, takie jak litery alfabetu, cyfry, czy inne symbole.
- **double**: Do przechowywania liczb zmiennoprzecinkowych z większą precyzją niż float.

## Deklaracja Zmiennych
Aby zadeklarować zmienną w C, należy podać jej typ, a następnie nazwę. Na przykład:
```c
int liczba;
float wartosc;
char znak;
```

## Inicjalizacja Zmiennych
Inicjalizacja to proces przypisywania początkowej wartości do zmiennej. Może to zostać zrobione w momencie deklaracji:
```c
int liczba = 10;
float wartosc = 5.25;
char znak = 'A';
```

## Wartości Stałe
W C możemy również zdefiniować stałe, czyli zmienne, których wartość nie zmienia się przez cały czas trwania programu. Stałe deklarujemy za pomocą słowa kluczowego `const`. Na przykład:
```c
const int MAX = 100;
```

## Podsumowanie
Zrozumienie zmiennych i typów danych jest kluczowe w nauce programowania w C. Są one fundamentem, na którym buduje się większość programów. W następnych rozdziałach będziemy używać tych koncepcji do tworzenia bardziej skomplikowanych programów.
