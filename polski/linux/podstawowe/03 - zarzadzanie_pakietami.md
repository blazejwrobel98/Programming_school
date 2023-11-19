
# Podstawy zarz±dzania pakietami

Zarz±dzanie pakietami w Linuxie jest kluczowym elementem utrzymania systemu i instalacji nowego oprogramowania. Ka¿da dystrybucja Linuxa ma w³asny system zarz±dzania pakietami, który u³atwia instalacjê, aktualizacjê i usuwanie oprogramowania.

## Popularne systemy zarz±dzania pakietami

- **APT (Advanced Package Tool)**: U¿ywany w Debianie, Ubuntu i ich pochodnych. Zarz±dza pakietami `.deb`.
- **YUM (Yellowdog Updater, Modified)** / **DNF (Dandified YUM)**: U¿ywane w dystrybucjach typu Red Hat, jak Fedora. Zarz±dzaj± pakietami `.rpm`.
- **Pacman**: U¿ywany w Arch Linux i jego pochodnych.

## Podstawowe operacje zarz±dzania pakietami

- **Instalacja oprogramowania**: `sudo apt install [pakiet]`, `sudo dnf install [pakiet]`, `sudo pacman -S [pakiet]`.
- **Aktualizacja systemu i pakietów**: `sudo apt update && sudo apt upgrade`, `sudo dnf upgrade`, `sudo pacman -Syu`.
- **Usuwanie oprogramowania**: `sudo apt remove [pakiet]`, `sudo dnf remove [pakiet]`, `sudo pacman -R [pakiet]`.
- **Wyszukiwanie pakietów**: `apt search [s³owo kluczowe]`, `dnf search [s³owo kluczowe]`, `pacman -Ss [s³owo kluczowe]`.

## Zarz±dzanie zale¿no¶ciami

- Systemy zarz±dzania pakietami automatycznie rozwi±zuj± zale¿no¶ci miêdzy pakietami, zapewniaj±c, ¿e wszystkie potrzebne biblioteki i pakiety s± zainstalowane.

## Repozytoria pakietów

- Repozytoria s± zdalnymi serwerami przechowuj±cymi pakiety. Ka¿da dystrybucja posiada w³asne oficjalne repozytoria, a u¿ytkownicy mog± dodawaæ repozytoria stron trzecich.

## Dobre praktyki

- Regularne aktualizacje systemu i oprogramowania zapewniaj± bezpieczeñstwo i stabilno¶æ.
- Nale¿y uwa¿aæ przy dodawaniu nieoficjalnych repozytoriów, aby unikn±æ niestabilnego lub niebezpiecznego oprogramowania.

Zrozumienie zarz±dzania pakietami pozwala na efektywn± i bezpieczn± pracê z systemem Linux, a tak¿e jest kluczowe w utrzymaniu systemu aktualnym i bezpiecznym.
