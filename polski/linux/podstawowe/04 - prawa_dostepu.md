
# Podstawy systemu praw dost�pu w Linuxie

System uprawnie� w Linuxie jest podstawowym mechanizmem kontroli dost�pu do plik�w i katalog�w, co jest kluczowe dla bezpiecze�stwa systemu.

## Zrozumienie uprawnie�

- W systemie Linux, ka�dy plik i katalog ma przypisane uprawnienia dost�pu, kt�re okre�laj�, kto i w jaki spos�b mo�e z nich korzysta�.
- Uprawnienia s� definiowane dla trzech typ�w u�ytkownik�w: w�a�ciciela pliku (owner), grupy (group) i innych (others).

## Rodzaje uprawnie�

- **Czytanie (r)**: Pozwala na odczyt zawarto�ci pliku lub listowanie zawarto�ci katalogu.
- **Pisanie (w)**: Umo�liwia modyfikacj� pliku lub dodawanie/usuwanie plik�w z katalogu.
- **Wykonywanie (x)**: Pozwala na uruchamianie pliku jako programu lub dost�p do katalogu.

## Zarz�dzanie uprawnieniami

- Uprawnienia mog� by� zmieniane przy u�yciu polecenia `chmod`. Na przyk�ad, `chmod 755 plik` nadaje w�a�cicielowi pe�ne uprawnienia, a grupie i innym u�ytkownikom pozwala tylko na czytanie i wykonywanie.
- Mo�na r�wnie� zmienia� w�a�ciciela pliku (`chown`) oraz grup� (`chgrp`).

## Specjalne uprawnienia

- **SetUID**: Ustawione na pliku wykonawczym powoduje, �e program uruchamia si� z uprawnieniami w�a�ciciela pliku.
- **SetGID**: Podobnie jak SetUID, ale dla grupy.
- **Sticky bit**: Ustawiony na katalogu zapobiega usuwaniu plik�w przez u�ytkownik�w, kt�rzy nie s� ich w�a�cicielami.

## Dobre praktyki

- Zawsze ustawiaj minimalne niezb�dne uprawnienia dla plik�w i katalog�w.
- Uwa�aj przy nadawaniu uprawnie� wykonawczych, szczeg�lnie w katalogach dost�pnych dla wielu u�ytkownik�w.

Zrozumienie i poprawne zarz�dzanie uprawnieniami jest kluczowe dla utrzymania bezpiecze�stwa systemu.
