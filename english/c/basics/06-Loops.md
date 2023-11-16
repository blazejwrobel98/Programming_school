
# Pętle w Języku C

Pętle są fundamentalnym elementem programowania w C, pozwalającym na wielokrotne wykonanie fragmentu kodu. W C istnieją trzy główne typy pętli: `for`, `while` i `do-while`.

## Pętla for
Pętla `for` jest używana, gdy wiemy, ile razy chcemy wykonać pętlę.
```c
for (inicjalizacja; warunek; inkrementacja) {
    // kod do wykonania
}
```

## Pętla while
Pętla `while` wykonuje kod, dopóki spełniony jest określony warunek.
```c
while (warunek) {
    // kod do wykonania
}
```

## Pętla do-while
Pętla `do-while` działa podobnie do `while`, ale gwarantuje, że kod wewnątrz pętli zostanie wykonany przynajmniej raz.
```c
do {
    // kod do wykonania
} while (warunek);
```

## Przykłady Użycia Pętli
```c
// Pętla for
for (int i = 0; i < 10; i++) {
    printf("%d
", i);
}

// Pętla while
int i = 0;
while (i < 10) {
    printf("%d
", i);
    i++;
}

// Pętla do-while
int i = 0;
do {
    printf("%d
", i);
    i++;
} while (i < 10);
```

## Wnioski
Pętle są niezwykle ważne w programowaniu w C, ponieważ pozwalają na efektywne wykonywanie powtarzalnych zadań. Wybór odpowiedniego typu pętli zależy od konkretnego przypadku i warunków, jakie muszą być spełnione, aby pętla działała poprawnie.
