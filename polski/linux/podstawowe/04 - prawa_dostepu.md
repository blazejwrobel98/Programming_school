
# Podstawy systemu praw dostêpu w Linuxie

System uprawnieñ w Linuxie jest podstawowym mechanizmem kontroli dostêpu do plików i katalogów, co jest kluczowe dla bezpieczeñstwa systemu.

## Zrozumienie uprawnieñ

- W systemie Linux, ka¿dy plik i katalog ma przypisane uprawnienia dostêpu, które okre¶laj±, kto i w jaki sposób mo¿e z nich korzystaæ.
- Uprawnienia s± definiowane dla trzech typów u¿ytkowników: w³a¶ciciela pliku (owner), grupy (group) i innych (others).

## Rodzaje uprawnieñ

- **Czytanie (r)**: Pozwala na odczyt zawarto¶ci pliku lub listowanie zawarto¶ci katalogu.
- **Pisanie (w)**: Umo¿liwia modyfikacjê pliku lub dodawanie/usuwanie plików z katalogu.
- **Wykonywanie (x)**: Pozwala na uruchamianie pliku jako programu lub dostêp do katalogu.

## Zarz±dzanie uprawnieniami

- Uprawnienia mog± byæ zmieniane przy u¿yciu polecenia `chmod`. Na przyk³ad, `chmod 755 plik` nadaje w³a¶cicielowi pe³ne uprawnienia, a grupie i innym u¿ytkownikom pozwala tylko na czytanie i wykonywanie.
- Mo¿na równie¿ zmieniaæ w³a¶ciciela pliku (`chown`) oraz grupê (`chgrp`).

## Specjalne uprawnienia

- **SetUID**: Ustawione na pliku wykonawczym powoduje, ¿e program uruchamia siê z uprawnieniami w³a¶ciciela pliku.
- **SetGID**: Podobnie jak SetUID, ale dla grupy.
- **Sticky bit**: Ustawiony na katalogu zapobiega usuwaniu plików przez u¿ytkowników, którzy nie s± ich w³a¶cicielami.

## Dobre praktyki

- Zawsze ustawiaj minimalne niezbêdne uprawnienia dla plików i katalogów.
- Uwa¿aj przy nadawaniu uprawnieñ wykonawczych, szczególnie w katalogach dostêpnych dla wielu u¿ytkowników.

Zrozumienie i poprawne zarz±dzanie uprawnieniami jest kluczowe dla utrzymania bezpieczeñstwa systemu.
