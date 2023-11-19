
# Podstawy zarz�dzania pakietami

Zarz�dzanie pakietami w Linuxie jest kluczowym elementem utrzymania systemu i instalacji nowego oprogramowania. Ka�da dystrybucja Linuxa ma w�asny system zarz�dzania pakietami, kt�ry u�atwia instalacj�, aktualizacj� i usuwanie oprogramowania.

## Popularne systemy zarz�dzania pakietami

- **APT (Advanced Package Tool)**: U�ywany w Debianie, Ubuntu i ich pochodnych. Zarz�dza pakietami `.deb`.
- **YUM (Yellowdog Updater, Modified)** / **DNF (Dandified YUM)**: U�ywane w dystrybucjach typu Red Hat, jak Fedora. Zarz�dzaj� pakietami `.rpm`.
- **Pacman**: U�ywany w Arch Linux i jego pochodnych.

## Podstawowe operacje zarz�dzania pakietami

- **Instalacja oprogramowania**: `sudo apt install [pakiet]`, `sudo dnf install [pakiet]`, `sudo pacman -S [pakiet]`.
- **Aktualizacja systemu i pakiet�w**: `sudo apt update && sudo apt upgrade`, `sudo dnf upgrade`, `sudo pacman -Syu`.
- **Usuwanie oprogramowania**: `sudo apt remove [pakiet]`, `sudo dnf remove [pakiet]`, `sudo pacman -R [pakiet]`.
- **Wyszukiwanie pakiet�w**: `apt search [s�owo kluczowe]`, `dnf search [s�owo kluczowe]`, `pacman -Ss [s�owo kluczowe]`.

## Zarz�dzanie zale�no�ciami

- Systemy zarz�dzania pakietami automatycznie rozwi�zuj� zale�no�ci mi�dzy pakietami, zapewniaj�c, �e wszystkie potrzebne biblioteki i pakiety s� zainstalowane.

## Repozytoria pakiet�w

- Repozytoria s� zdalnymi serwerami przechowuj�cymi pakiety. Ka�da dystrybucja posiada w�asne oficjalne repozytoria, a u�ytkownicy mog� dodawa� repozytoria stron trzecich.

## Dobre praktyki

- Regularne aktualizacje systemu i oprogramowania zapewniaj� bezpiecze�stwo i stabilno��.
- Nale�y uwa�a� przy dodawaniu nieoficjalnych repozytori�w, aby unikn�� niestabilnego lub niebezpiecznego oprogramowania.

Zrozumienie zarz�dzania pakietami pozwala na efektywn� i bezpieczn� prac� z systemem Linux, a tak�e jest kluczowe w utrzymaniu systemu aktualnym i bezpiecznym.
