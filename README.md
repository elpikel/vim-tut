vim-tut
=======
1. Agenda
Po co vi[m]?
Podstawowe komendy.
Dokumentacja.
Konfiguracja.



Vim is a highly configurable text editor built to enable efficient text editing. It is an improved version of the vi editor distributed with most UNIX systems.
Vim is often called a "programmer's editor," and so useful for programming that many consider it an entire IDE. It's not just for programmers, though. Vim is perfect for all kinds of text editing, from composing email to editing configuration files.

Działa na większości systemów operacyjnych: Windows, OSX, Unix.

Został stworzony w 1976 roku.

Po co mi vim?

Jest bardzo wydajny nie ze względu na szybkość działania ale ze względu na interfejs który oferuje. Vim zapewnia ogromny wachlarz przydatnych narzędzi do edycji tekstu o czym większośc współczenych ide zapomniało. Czym lepiej nauczysz się tych narzędzi tym szybciej będziesz w stanie wykonać swoje zadanie - czym szybciej uda ci sie wykonać zadanie tym więcej wolego czasu będziesz miał? 

Szybki start

Unix:
vim [plik_do_edycji]
Windows:
prawy przycisk myszy i Edit with vim

Szybka ucieczka:

Dla większości ludzi nie wydaje się to przyjazne środowisko. Aby wyjść musimy przenieść się do trybu poleceń:

Esc
:q

Jeżeli edytowaliśmy plik w tym miejscu dostaniemy wyjątek o niezapisanym pliku. Aby wymusić wyjście:

:q!

Podstawy poruszania się po tekście:

h,j,k,l - zamiast strzałek
crtl-[b/f] - poprzednia/następna strona
b/w - poprzednie następne słowo
$ - koniec lini
0 - początek lini
^ - pierwsza litera w lini
L/H/M - dół/góra/środek ekranu
G/gg - koniec/początek pliku

Podstawy edycji:

i - tryb edycji [Esc aby wyjść]
I - tryb edycji od początku lini
a - tryb edycji za kursorem
A - tryb edycji na koniec lini
s - usuwa znak i przechodzi do trybu edycji
S - usuwa linie i przechodzi w tryb edycji
x - usuwa znak pod kursorem
X - usuwa znak przed kursorem
dd - usuwa linie
D - usuwa od aktulanego miejsca
y - kopiuje
p - wkleje
u - cofa ostatnią zmiane
ctrl-r - przywraca ostatnią zmianę

Tryb wizualny:
v - tryb wizualny znakowy
V - tryb wizualny liniowy
ctrl-v - tryb wizualny blokowy

Szukanie:
/[fraza] - przenosi do szukanej frazy - n N - przód tył

Zamiana:
:%s/[z]/[na]/g - zamienia [z] na [na] we wszystkich liniach
:s/[z]/[na]/g - zamienia [z] na [na] w aktualnej lini 

Przykłady:
daw - usuwa wyraz
di( - usuwa wewnatrz (
dt, - usuwa do znaku ,
df, - usuwa ze znakiem ,


---------
vimtutor
---------


