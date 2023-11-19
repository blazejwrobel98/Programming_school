
# Lista i opis podstawowych komend w terminalu Linux

Zrozumienie i efektywne wykorzystanie terminala jest kluczowe dla ka¿dego u¿ytkownika Linuxa. Terminal, znany równie¿ jako pow³oka (shell), to interfejs tekstowy do systemu, który umo¿liwia wykonywanie poleceñ, zarz±dzanie plikami, a tak¿e uruchamianie programów.

## Podstawowe komendy i ich zastosowanie

- `ls`: Listuje zawarto¶æ katalogu. U¿yj `ls -l` dla szczegó³owego widoku, `ls -a` do wy¶wietlenia ukrytych plików.
- `cd [¶cie¿ka]`: Zmienia bie¿±cy katalog. `cd ..` przenosi do katalogu nadrzêdnego, a `cd` bez argumentu przenosi do katalogu domowego u¿ytkownika.
- `pwd`: Wy¶wietla pe³n± ¶cie¿kê bie¿±cego katalogu.
- `cp [¼ród³o] [cel]`: Kopiuje pliki lub katalogi. U¿yj `cp -r` do kopiowania katalogów.
- `mv [¼ród³o] [cel]`: Przenosi lub zmienia nazwê plików i katalogów.
- `rm [plik/katalog]`: Usuwa pliki lub katalogi. Uwa¿aj na `rm -rf`, które usuwa rekursywnie i bez pytania o potwierdzenie!
- `chmod [uprawnienia] [plik/katalog]`: Zmienia uprawnienia pliku lub katalogu. Uprawnienia mog± byæ okre¶lone numerycznie (np. `755`) lub symbolicznie (np. `u+rw,g+r,o-r`).
- `man [komenda]`: Wy¶wietla instrukcjê (manual) danej komendy, jest to nieocenione ¼ród³o informacji o komendach.

## Przydatne kombinacje i sztuczki
- £±czenie komend: Mo¿esz u¿yæ `|` do przekazania wyniku jednej komendy jako wej¶cia do innej, np. `ls -l | grep "txt"` wyszuka w listingu pliki z rozszerzeniem `.txt`.
- Przekierowanie wyj¶cia: `>` i `>>` s³u¿± do zapisywania wyj¶cia komendy do pliku, np. `ls -l > pliki.txt`.

## Wskazówki dla pocz±tkuj±cych
- Æwicz u¿ywanie tych komend, aby sta³y siê Twoim drugim jêzykiem.
- Korzystaj z `man` oraz `--help` dla zdobycia dodatkowych informacji o komendach.

Opanowanie podstawowych komend terminala otwiera drzwi do zaawansowanego i efektywnego korzystania z systemu Linux.
