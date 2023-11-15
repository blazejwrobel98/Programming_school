
# Tagowanie i Git Hooks w Git

## Opis
Zarówno tagowanie, jak i Git Hooks, są zaawansowanymi funkcjami Git, które umożliwiają lepsze zarządzanie projektem i automatyzację zadań. W tym dokumencie omówimy, jak wykorzystać te funkcje w praktyce.

## Tagowanie w Git
Tagi w Git służą do oznaczania ważnych punktów w historii projektu, takich jak wydania czy ważne zmiany.

### Tworzenie Tagów
- **Lekkie Tagi**: Szybkie oznaczenie commita.
  ```
  git tag nazwa_tagu
  ```
- **Annotowane Tagi**: Zawierają dodatkowe informacje, takie jak autor, data i wiadomość.
  ```
  git tag -a nazwa_tagu -m "wiadomość"
  ```

### Użycie Tagów
- Wykorzystanie tagów do identyfikacji wersji wydań.
- Przejście do konkretnego tagu w historii projektu.

## Git Hooks
Git Hooks to skrypty, które są wykonywane automatycznie przy określonych akcjach w Git, takich jak commit, push czy merge.

### Rodzaje Git Hooks
- **Pre-commit Hooks**: Uruchamiane przed zatwierdzeniem zmian.
- **Post-commit Hooks**: Uruchamiane po zatwierdzeniu zmian.
- **Pre-push Hooks**: Uruchamiane przed wysłaniem zmian do zdalnego repozytorium.

### Przykłady Zastosowań
- Automatyczne sprawdzanie stylu kodu przed commit.
- Uruchamianie testów przed push.

## Wnioski
Tagowanie i Git Hooks to potężne narzędzia, które mogą znacząco przyczynić się do poprawy organizacji i efektywności pracy nad projektem. Pozwalają na lepszą kontrolę wersji i automatyzację rutynowych zadań związanych z zarządzaniem kodem.
