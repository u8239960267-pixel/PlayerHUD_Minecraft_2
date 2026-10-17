PLAYER HUD — Fabric dla Minecraft Java 1.21.11

Projekt źródłowy moda klienckiego PlayerHUD. Workflow GitHub Actions buduje plik JAR po pushu, pull requeście lub ręcznym uruchomieniu.

Funkcje prototypu:
- Menu ustawień pod klawiszem H (zmienisz w Opcje -> Sterowanie).
- Panel przeciwnika: skin, nick, zdrowie/absorpcja, pancerz i przedmioty w rękach.
- Trzy style wyświetlania zdrowia i pancerza.
- Zmiana skali i przesuwanie panelu w menu ustawień.

Budowanie przez GitHub:
1. Wgraj zawartość tego folderu do głównego katalogu repozytorium (razem z folderem .github).
2. Otwórz zakładkę Actions. Workflow „Build PlayerHUD for Minecraft 1.21.11” uruchamia się automatycznie po pushu; można go też uruchomić ręcznie.
3. Po zakończeniu otwórz przebieg i pobierz artefakt „PlayerHUD-Fabric-1.21.11” z sekcji Artifacts.
4. Wypakuj pobrany artefakt ZIP i umieść plik JAR w folderze .minecraft/mods. Zainstaluj Fabric Loader 1.21.11 oraz zgodną wersję Fabric API.

Ważne:
- To jest port konfiguracji i kodu źródłowego z 1.21.4 do 1.21.11. Nie mogłem uruchomić kompilacji w tym środowisku, bo nie ma połączenia z repozytoriami zależności. GitHub Actions pokaże ewentualne błędy kompilacji.
- Nie używaj jednocześnie kilku wersji tego moda.
