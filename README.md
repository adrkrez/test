mapa.py wersja 0.11
Generowanie mapy ze śladami wycieczek pieszych (lub jakichkolwiek innych).
Stworzone z pomocą Claude.
Konieczny zainstalowany najnowszy python

Instrukcja:

Instalujemy Python

Do katalogu np. Moje Trasy kopiujemy ślady wycieczek w formacie gpx.

Do tego samego katalogu kopiujemy plik mapa.py

klikamy Start prawym klikiem myszy (Windows 10)

Wybieramy Eksploatator Plików

Wchodzimy do katalogu gdzie znajdują się ślady GPS i mapa.py

Klikamy na pasek adresu aby podświetlił się na niebiesko

Wpisujemy cmd i enter. Uruchomi się okno

Wpisujemy: 

python mapa.py i enter

Mapa zostanie wygenerowana w formie pliku moje trasy.html

przeglądanie mapy

Na komputerze

Wpisujemy cmd i enter. Uruchomi się okno

włączamy serwer:  python -m http.server 8000

wchodzimy przez przeglądarkę na adres: http://localhost:8000/moje_trasy.html

gdy skończymy zamykamy serwer: będąc w terminalu - ctrl+c i enter. upewnić się ze strona przestala działać.

mapa może być też umieszczona w internecie np na github 

przykład: https://adrkrez.github.io/test/moje_trasy.html

umieszczamy plik moje_trasy.html na serwerze
