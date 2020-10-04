# Gra słowa
        
    Nazwa: Gra słowa
    Język programowania: Java
    Środowisko programistyczne: NetBeans 8.2
    
    Autor: Łukasz Gołojuch
    Licencja: Open Source
    
## Opis gry

Zasady gry singleplayer:

Gra toczy się dopóki saldo Twojego konta jest większe 
od $0.

Zasady gry multiplayer:

Na starcie gracze otrzymują po $1000.
Gra toczy sie, dopoki jeden z graczy 
nie zbankrutuje (saldo jego konta dojdzie
do $0) Wygrywa osoba z większym saldem.

Ekonomia gry:

Nie odgadnięcie hasła: -$500
Kupno litery: -$200
Błędna litera: -$100
Odgadnięcie hasła (litery): +$50
Odgadnięcie hasła (słowo): +$100

## Moduły programu

poczatek.java - początek gry, główne menu z możliwością wyboru między zasadami gry, a przejściem dalej

ekonomia.java - informacje odnośnie ekonomii gry

gra.java - silnik gry wykonujący większość obliczeń

gra_single.java - główne okno dla gry dla jednego gracza

ile_osob.java - menu do wyboru ilości osób

imie_multi.java - pobieranie imion w trybie dla dwóch graczy

imie_single.java - pobieranie imion w trybie dla jednego gracza

koniec.java - koniec gry 

koniec_single.java - koniec gry dla singleplayera

podawanie.java - podawanie hasła dla drugiego gracza

zasady_multi.java - informacje z zasadami gry dla muliplayera

zasady_single.java - informacje z zasadami dla gracza singleplayer

zasady_wyb.java - menu z wyborem opcji dla menu z informacjami



