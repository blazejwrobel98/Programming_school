
# Zaawansowane skryptowanie w Bash

Skryptowanie w Bash to nie tylko automatyzacja rutynowych zada�, ale r�wnie� tworzenie z�o�onych skrypt�w, kt�re mog� znacz�co usprawni� prac� w systemie Linux.

## Podstawy skrypt�w Bash

- **Zmienne**: Przechowywanie i manipulowanie danymi. Np. `name="World"; echo "Hello, $name"`.
- **P�tle**: Automatyzacja powtarzalnych zada�. `for`, `while`, `until` to kluczowe p�tle w Bash.
- **Instrukcje warunkowe**: `if`, `else`, `elif` pozwalaj� na wykonanie kodu w zale�no�ci od okre�lonych warunk�w.
- **Funkcje**: Grupowanie polece� w �atwo wywo�ywalne bloki kodu.

## Przyk�ady zaawansowanych skrypt�w

### Skrypt backupu

```bash
#!/bin/bash
backup_folder="/mnt/backup"
source_folder="/home/user/data"

tar czf $backup_folder/backup-$(date +%Y%m%d).tar.gz $source_folder
```

Ten skrypt tworzy skompresowany archiwum z zawarto�ci `source_folder` w lokalizacji `backup_folder` z dat� w nazwie.

### Monitorowanie dost�pno�ci serwisu

```bash
#!/bin/bash
url="http://example.com"
response=$(curl -o /dev/null -s -w "%{http_code}
" $url)

if [ "$response" -eq 200 ]; then
    echo "Serwis $url jest dost�pny."
else
    echo "Serwis $url nie odpowiada."
fi
```

Skrypt korzysta z `curl` do sprawdzenia, czy strona internetowa jest dost�pna, i wy�wietla odpowiedni komunikat.

## Debugowanie skrypt�w

- U�yj `set -x` na pocz�tku skryptu, aby zobaczy�, jakie polecenia s� wykonywane.
- `echo` i `printf` s� przydatne do wy�wietlania warto�ci zmiennych i stanu skryptu.

## Dobre praktyki

- Zawsze cytuj zmienne, aby unikn�� nieoczekiwanego rozszerzania.
- Traktuj dane wej�ciowe jako niezaufane i sprawdzaj je przed u�yciem.

Opanowanie skryptowania w Bash otwiera nowe mo�liwo�ci zarz�dzania systemem Linux i automatyzacji zada�.
