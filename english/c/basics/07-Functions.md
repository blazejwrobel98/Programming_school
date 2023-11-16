
# Funkcje w Języku C

Funkcje w języku C są niezbędne do tworzenia modularnego i czytelnego kodu. Pozwalają na dzielenie programu na mniejsze, zarządzalne części, które można wielokrotnie wykorzystywać.

## Definicja Funkcji
Funkcja składa się z nagłówka i ciała. Nagłówek określa nazwę funkcji, jej typ zwracany oraz parametry (jeśli takie istnieją). Ciało funkcji zawiera kod, który jest wykonywany, gdy funkcja jest wywoływana.

```c
typ_zwracany nazwa_funkcji(typ_parametru1 nazwa_parametru1, typ_parametru2 nazwa_parametru2) {
    // ciało funkcji
}
```

## Przykład Funkcji
Poniżej znajduje się przykład prostej funkcji, która sumuje dwie liczby.

```c
int dodaj(int a, int b) {
    return a + b;
}
```

## Wywoływanie Funkcji
Funkcję wywołujemy, podając jej nazwę i przekazując odpowiednie argumenty.

```c
int wynik = dodaj(5, 3);
```

## Funkcje bez Zwracanej Wartości
Funkcje w C mogą nie zwracać żadnej wartości. W takim przypadku używamy typu `void`.

```c
void wyswietlWiadomosc() {
    printf("Witaj w C!");
}
```

## Parametry Funkcji
Funkcje mogą przyjmować parametry, które są przekazywane podczas wywoływania funkcji. Parametry te mogą być różnych typów.

## Wnioski
Funkcje są podstawowym narzędziem w języku C, pozwalającym na tworzenie efektywnego i czytelnego kodu. Ułatwiają one zarządzanie dużymi projektami i pozwalają na wielokrotne używanie kodu bez jego powielania.
