
# Lista i opis podstawowych komend w terminalu Linux

Zrozumienie i efektywne wykorzystanie terminala jest kluczowe dla ka�dego u�ytkownika Linuxa. Terminal, znany r�wnie� jako pow�oka (shell), to interfejs tekstowy do systemu, kt�ry umo�liwia wykonywanie polece�, zarz�dzanie plikami, a tak�e uruchamianie program�w.

## Podstawowe komendy i ich zastosowanie

- `ls`: Listuje zawarto�� katalogu. U�yj `ls -l` dla szczeg�owego widoku, `ls -a` do wy�wietlenia ukrytych plik�w.
- `cd [�cie�ka]`: Zmienia bie��cy katalog. `cd ..` przenosi do katalogu nadrz�dnego, a `cd` bez argumentu przenosi do katalogu domowego u�ytkownika.
- `pwd`: Wy�wietla pe�n� �cie�k� bie��cego katalogu.
- `cp [�r�d�o] [cel]`: Kopiuje pliki lub katalogi. U�yj `cp -r` do kopiowania katalog�w.
- `mv [�r�d�o] [cel]`: Przenosi lub zmienia nazw� plik�w i katalog�w.
- `rm [plik/katalog]`: Usuwa pliki lub katalogi. Uwa�aj na `rm -rf`, kt�re usuwa rekursywnie i bez pytania o potwierdzenie!
- `chmod [uprawnienia] [plik/katalog]`: Zmienia uprawnienia pliku lub katalogu. Uprawnienia mog� by� okre�lone numerycznie (np. `755`) lub symbolicznie (np. `u+rw,g+r,o-r`).
- `man [komenda]`: Wy�wietla instrukcj� (manual) danej komendy, jest to nieocenione �r�d�o informacji o komendach.

## Przydatne kombinacje i sztuczki
- ��czenie komend: Mo�esz u�y� `|` do przekazania wyniku jednej komendy jako wej�cia do innej, np. `ls -l | grep "txt"` wyszuka w listingu pliki z rozszerzeniem `.txt`.
- Przekierowanie wyj�cia: `>` i `>>` s�u�� do zapisywania wyj�cia komendy do pliku, np. `ls -l > pliki.txt`.

## Wskaz�wki dla pocz�tkuj�cych
- �wicz u�ywanie tych komend, aby sta�y si� Twoim drugim j�zykiem.
- Korzystaj z `man` oraz `--help` dla zdobycia dodatkowych informacji o komendach.

Opanowanie podstawowych komend terminala otwiera drzwi do zaawansowanego i efektywnego korzystania z systemu Linux.
