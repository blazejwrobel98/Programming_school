
# Operatory w Języku C

Operatory w języku C są niezbędne do wykonywania operacji na zmiennych i wartościach. W tym rozdziale przyjrzymy się różnym rodzajom operatorów dostępnych w C.

## Rodzaje Operatorów
W języku C istnieje kilka rodzajów operatorów, które można podzielić na następujące kategorie:

### 1. Operatory Arytmetyczne
Służą do wykonywania podstawowych operacji matematycznych:
- **+** (dodawanie)
- **-** (odejmowanie)
- \* (mnożenie)
- **/** (dzielenie)
- **%** (reszta z dzielenia)

### 2. Operatory Relacyjne
Służą do porównywania wartości:
- **==** (równe)
- **!=** (nierówne)
- **>** (większe niż)
- **<** (mniejsze niż)
- **>=** (większe lub równe)
- **<=** (mniejsze lub równe)

### 3. Operatory Logiczne
Służą do tworzenia złożonych wyrażeń logicznych:
- **&&** (logiczne AND)
- **||** (logiczne OR)
- **!** (logiczne NOT)

### 4. Operatory Bitowe
Operują na bitach danych:
- **&** (bitowe AND)
- **|** (bitowe OR)
- **^** (bitowe XOR)
- **~** (bitowe NOT)
- **<<** (przesunięcie bitowe w lewo)
- **>>** (przesunięcie bitowe w prawo)

### 5. Operatory Przypisania
Służą do przypisywania wartości do zmiennych:
- **=** (proste przypisanie)
- **+=**, **-=**, **\*=**, **/=**, **%=** (przypisanie z operacją)

## Przykłady Użycia Operatorów
```c
int a = 5, b = 10;
int wynik;

// Arytmetyczne
wynik = a + b; // Dodawanie
wynik = a - b; // Odejmowanie

// Relacyjne
bool czyRowne = (a == b); // Sprawdzanie równości

// Logiczne
bool prawda = (a < b) && (b > 5); // Użycie logicznego AND

// Bitowe
int bitoweAnd = a & b; // Bitowe AND

// Przypisanie
a += 5; // a = a + 5
```

## Wnioski
Operatory w C pozwalają na manipulację danymi i stanowią ważny element w tworzeniu logiki programu. Zrozumienie różnych typów operatorów i ich zastosowania jest kluczowe w nauce programowania w języku C.
