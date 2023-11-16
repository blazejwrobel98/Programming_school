
# Instrukcje Warunkowe w Języku C

Instrukcje warunkowe w języku C pozwalają na sterowanie przepływem programu w zależności od spełnienia określonych warunków. Są one kluczowym elementem logiki w programowaniu.

## if
Instrukcja `if` pozwala na wykonanie kodu, jeśli podany warunek jest prawdziwy.
```c
if (warunek) {
    // kod do wykonania, gdy warunek jest prawdziwy
}
```

## else
`else` używane jest w połączeniu z `if` do wykonania kodu, gdy warunek `if` jest fałszywy.
```c
if (warunek) {
    // kod do wykonania, gdy warunek jest prawdziwy
} else {
    // kod do wykonania, gdy warunek jest fałszywy
}
```

## else if
`else if` pozwala na sprawdzenie wielu warunków jeden po drugim.
```c
if (warunek1) {
    // kod do wykonania, gdy warunek1 jest prawdziwy
} else if (warunek2) {
    // kod do wykonania, gdy warunek2 jest prawdziwy
} else {
    // kod do wykonania, gdy żaden z warunków nie jest spełniony
}
```

## switch
Instrukcja `switch` jest używana do wykonania różnych akcji w zależności od wartości zmiennej.
```c
switch (zmienna) {
    case wartość1:
        // kod do wykonania, gdy zmienna ma wartość1
        break;
    case wartość2:
        // kod do wykonania, gdy zmienna ma wartość2
        break;
    default:
        // kod do wykonania, gdy żadna z wartości nie pasuje
}
```

## Wnioski
Zrozumienie i umiejętne wykorzystanie instrukcji warunkowych jest niezbędne do tworzenia skutecznych i elastycznych programów w języku C. Pozwala to na adaptację programu do różnych sytuacji i danych wejściowych.
