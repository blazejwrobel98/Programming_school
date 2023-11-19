
# Zaawansowane skryptowanie w Bash

Skryptowanie w Bash to nie tylko automatyzacja rutynowych zadañ, ale równie¿ tworzenie z³o¿onych skryptów, które mog± znacz±co usprawniæ pracê w systemie Linux.

## Podstawy skryptów Bash

- **Zmienne**: Przechowywanie i manipulowanie danymi. Np. `name="World"; echo "Hello, $name"`.
- **Pêtle**: Automatyzacja powtarzalnych zadañ. `for`, `while`, `until` to kluczowe pêtle w Bash.
- **Instrukcje warunkowe**: `if`, `else`, `elif` pozwalaj± na wykonanie kodu w zale¿no¶ci od okre¶lonych warunków.
- **Funkcje**: Grupowanie poleceñ w ³atwo wywo³ywalne bloki kodu.

## Przyk³ady zaawansowanych skryptów

### Skrypt backupu

```bash
#!/bin/bash
backup_folder="/mnt/backup"
source_folder="/home/user/data"

tar czf $backup_folder/backup-$(date +%Y%m%d).tar.gz $source_folder
```

Ten skrypt tworzy skompresowany archiwum z zawarto¶ci `source_folder` w lokalizacji `backup_folder` z dat± w nazwie.

### Monitorowanie dostêpno¶ci serwisu

```bash
#!/bin/bash
url="http://example.com"
response=$(curl -o /dev/null -s -w "%{http_code}
" $url)

if [ "$response" -eq 200 ]; then
    echo "Serwis $url jest dostêpny."
else
    echo "Serwis $url nie odpowiada."
fi
```

Skrypt korzysta z `curl` do sprawdzenia, czy strona internetowa jest dostêpna, i wy¶wietla odpowiedni komunikat.

## Debugowanie skryptów

- U¿yj `set -x` na pocz±tku skryptu, aby zobaczyæ, jakie polecenia s± wykonywane.
- `echo` i `printf` s± przydatne do wy¶wietlania warto¶ci zmiennych i stanu skryptu.

## Dobre praktyki

- Zawsze cytuj zmienne, aby unikn±æ nieoczekiwanego rozszerzania.
- Traktuj dane wej¶ciowe jako niezaufane i sprawdzaj je przed u¿yciem.

Opanowanie skryptowania w Bash otwiera nowe mo¿liwo¶ci zarz±dzania systemem Linux i automatyzacji zadañ.
