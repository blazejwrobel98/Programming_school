
# Tablice i Wskazniki w Języku C

Tablice i wskaźniki to dwa fundamentalne pojęcia w języku C, które są ściśle ze sobą powiązane. Umożliwiają one efektywne zarządzanie pamięcią i dostęp do danych.

## Tablice
Tablica w C to zbiór elementów tego samego typu, przechowywanych w ciągłym bloku pamięci. Każdy element tablicy może być dostępny poprzez jego indeks.

### Deklaracja Tablicy
```c
typ nazwa_tablicy[rozmiar];
```

### Przykład
```c
int liczby[5];
```

## Wskaźniki
Wskaźnik to zmienna, która przechowuje adres pamięci innej zmiennej. Wskaźniki są niezwykle potężnym narzędziem w C, umożliwiającym bezpośrednią manipulację pamięcią.

### Deklaracja Wskaźnika
```c
typ *nazwa_wskaznika;
```

### Przykład
```c
int *wskaznik;
```

## Relacja między Tablicami a Wskaźnikami
Nazwa tablicy w C jest wskaźnikiem na pierwszy element tablicy. Można więc używać wskaźników do iteracji przez elementy tablicy.

### Przykład
```c
int liczby[5] = {1, 2, 3, 4, 5};
int *wsk = liczby; // wskazuje na pierwszy element tablicy
```

## Operacje na Wskaźnikach
Wskaźniki mogą być inkrementowane i dekrementowane, co umożliwia przesuwanie się po tablicy.

### Przykład
```c
for(int i = 0; i < 5; i++) {
    printf("%d
", *(wsk + i));
}
```

## Wnioski
Zrozumienie tablic i wskaźników jest kluczowe w programowaniu w C. Umożliwiają one efektywne zarządzanie pamięcią i dostęp do danych, co jest podstawą wielu zaawansowanych technik programistycznych.
