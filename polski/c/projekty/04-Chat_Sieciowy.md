
# Projekt: Chat Sieciowy

## Opis Projektu
Celem tego projektu jest stworzenie prostego chatu sieciowego w języku C, który umożliwi komunikację tekstową między dwoma lub więcej użytkownikami przez sieć.

## Założenia Projektu
- Implementacja klienta i serwera, które będą się ze sobą komunikować za pomocą gniazd sieciowych.
- Użytkownicy mogą wysyłać i odbierać wiadomości w czasie rzeczywistym.
- Możliwość obsługi wielu użytkowników jednocześnie.

## Funkcjonalności
1. **Serwer Chatu**: Uruchomienie serwera, który nasłuchuje na połączenia od klientów.
2. **Klient Chatu**: Implementacja klienta, który łączy się z serwerem i umożliwia wysyłanie oraz odbieranie wiadomości.
3. **Komunikacja Sieciowa**: Używanie gniazd TCP/UDP do przesyłania wiadomości między klientem a serwerem.
4. **Interfejs Użytkownika**: Prosty interfejs tekstowy dla klienta do wysyłania i odbierania wiadomości.

## Wskazówki Implementacyjne
- Użyj biblioteki socketów dla połączeń sieciowych.
- Zaimplementuj wielowątkowość na serwerze do obsługi wielu klientów.
- Zastosuj odpowiednie protokoły sieciowe (TCP lub UDP) w zależności od wymagań aplikacji.

## Cel Edukacyjny
Projekt ten ma na celu praktyczne zastosowanie wiedzy na temat programowania sieciowego, wielowątkowości oraz interakcji użytkownika z programem działającym w środowisku sieciowym.
