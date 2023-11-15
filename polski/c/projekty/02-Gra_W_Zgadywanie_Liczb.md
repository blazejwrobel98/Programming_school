
# Projekt: Gra w Zgadywanie Liczb

## Opis Projektu
Celem tego projektu jest stworzenie gry w zgadywanie liczb, w której komputer losowo wybiera liczbę, a użytkownik próbuje ją odgadnąć. Gra ta jest prostym przykładem interakcji użytkownika z programem.

## Założenia Projektu
- Program losowo generuje liczbę w określonym zakresie (np. od 1 do 100).
- Użytkownik ma za zadanie zgadnąć tę liczbę, wprowadzając swoje propozycje.
- Po każdej próbie, program informuje użytkownika, czy jego liczba jest za duża, za mała, czy prawidłowa.
- Gra kończy się, gdy użytkownik odgadnie liczbę lub po określonej liczbie prób.

## Funkcjonalności
1. **Generowanie Losowej Liczby**: Program powinien na początku gry losowo wybrać liczbę.
2. **Proces Zgadywania**: Użytkownik powinien mieć możliwość wprowadzenia swojej propozycji liczby.
3. **Ocena Propozycji**: Program powinien ocenić zgadywaną liczbę i dać odpowiednią wskazówkę użytkownikowi.
4. **Warunki Zakończenia Gry**: Gra kończy się sukcesem (odgadnięta liczba) lub po przekroczeniu liczby prób.

## Wskazówki Implementacyjne
- Użyj funkcji generowania liczb losowych, np. `rand()`.
- Implementuj pętlę, która pozwala na wielokrotne zgadywanie liczby do momentu odgadnięcia lub przekroczenia limitu prób.
- Pamiętaj o odpowiednich komunikatach dla użytkownika.

## Cel Edukacyjny
Projekt ten pozwoli na praktyczne zastosowanie takich elementów języka C jak generowanie liczb losowych, pętle, instrukcje warunkowe i podstawowe wejście/wyjście.
