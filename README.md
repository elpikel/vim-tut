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

1. Modes
  a. insert a
  b. normal
  c. visual
  d. command
