
# Programowanie Strukturalne w Języku C

Programowanie strukturalne w języku C to podejście do tworzenia programów, które podkreśla znaczenie logicznej struktury i przejrzystego przepływu kontroli. W tym rozdziale omówimy kluczowe aspekty programowania strukturalnego w C.

## Co to jest Programowanie Strukturalne?
Programowanie strukturalne opiera się na trzech podstawowych strukturach kontrolnych:
- Sekwencja: Wykonywanie instrukcji kolejno, jedna po drugiej.
- Selekcja: Wykorzystanie instrukcji warunkowych do wyboru różnych ścieżek wykonania.
- Iteracja: Używanie pętli do wielokrotnego wykonania kodu.

## Struktury
Struktura w C to zbiór zmiennych różnych typów, grupowanych pod jedną nazwą. Struktury są wykorzystywane do organizacji złożonych danych.

### Deklaracja Struktury
```c
struct NazwaStruktury {
    typ1 pole1;
    typ2 pole2;
    // inne pola
};
```

### Użycie Struktury
```c
struct NazwaStruktury zmienna;
zmienna.pole1 = wartosc1;
zmienna.pole2 = wartosc2;
```

## Typydefiniowane
`typedef` pozwala na nadanie nowej nazwy typowi lub strukturze.

### Przykład
```c
typedef struct {
    int pole1;
    float pole2;
} NowaNazwa;
```

## Wnioski
Programowanie strukturalne w C jest podstawą dla tworzenia czytelnego i efektywnego kodu. Ułatwia zarządzanie złożonymi danymi i kontrolę przepływu programu. Zrozumienie struktur i ich zastosowanie jest kluczowe w zaawansowanym programowaniu w języku C.
