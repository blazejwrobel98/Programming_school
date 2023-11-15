
# Rebase vs Merge w Git

## Opis
W pracy zespołowej z wykorzystaniem Git, często pojawia się pytanie: kiedy używać `rebase`, a kiedy `merge`? Obie metody służą do integracji zmian z jednej gałęzi do drugiej, ale w różny sposób. Ten dokument ma na celu wyjaśnienie różnic między nimi oraz kiedy najlepiej stosować każdą z tych metod.

## Rebase
`Rebase` polega na przeniesieniu lub „przepisywaniu” sekwencji zmian z jednej gałęzi na inną.

### Zalety
- Tworzy liniową historię zmian, co ułatwia śledzenie i rozumienie historii projektu.
- Unika tworzenia dodatkowych commitów scalających.

### Wady
- Może powodować problemy w historii publicznej, jeśli nie jest stosowany ostrożnie.
- Może być mylący dla osób nieznających dobrze Git.

## Merge
`Merge` łączy dwie gałęzie, tworząc nowy commit, który zawiera zmiany z obu gałęzi.

### Zalety
- Zachowuje pełną historię i kontekst zmian.
- Bezpieczniejszy dla publicznych i współdzielonych gałęzi.

### Wady
- Może tworzyć skomplikowaną historię ze względu na merge commity.
- Czasami może być trudniejszy w rozwiązaniu konfliktów.

## Kiedy Stosować
- **Rebase**: dla lokalnych poprawek i czystej historii przed scaleniem do publicznej gałęzi.
- **Merge**: gdy scalasz publiczne gałęzie lub chcesz zachować pełną historię zmian.

## Wnioski
Wybór między `rebase` a `merge` powinien być podyktowany konkretną sytuacją i preferencjami zespołu. Ważne jest, aby zrozumieć konsekwencje każdej z metod i stosować je odpowiednio do kontekstu pracy.
