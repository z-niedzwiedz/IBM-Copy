# IBM-Copy
File transfer tool between CP/M, TOS and PC FAT-12 filesystems (requires CP/M on Timex FDD3000), 1991

INSTRUKCJA OBSLUGI PROGRAMU "IBM COPY" v.2.1
********************************************
autor:       ,    ,
Zbigniew Niedzwiedz, zam. Reja 16, 20-458 Lublin
************************************************

 Program "IBM COPY" jest programem kopiujacym umozliwiajacym
transfer plikow pomiedzy IBM (system MS-DOS lub PC-DOS)
a ZX Spectrum (system CP/M lub TOS). Poza standardowymi
operacjami dyskowymi (kopiowanie, kasowanie, zmiana nazwy,
zrzut na ekran lub drukarke pliku, wyswietlenie katalogu
formatowanie dyskietki i sprawdzenie poprawnosci zapisu
dostepne sa dodatkowe mozliwosci:
-wyswietlenie informacji o dyskietce MS-DOS (boot sector);
-zmiana czasu miedzy przesunieciem glowicy ze sciezki na sciezke;
-odczyt dowolnego sektora i zapis jego zawartosci do pliku;
-operacja odwrotna do powyzszej;
-odczyt calej sciezki i zapis jej zawartosci do pliku;
-formatowanie sciezki wedlug wzoru zapisanego w pliku;
-ustawienie parametrow TOS lub CP/M dla aktualnie wybranego
napedu;
-wyswietlenie tychze parametrow;
-przelaczenie wyswietlania wynikow ekran/drukarka;
-wyjscie do systemu operacyjnego.

 Po ustawieniu w napedzie CP/M parametrow TOS-u wszystkie
operacje dotyczaca CP/M sa wykonywanň na dyskietkach TOS
Parametry te pozostaja w pamieci rowniez po wyjsciu z
programu (mozna wtedy uzyc np. programu NSWEEP do obslugi
plikow z systemiu TOS) az do zmiany parametrowá na
poprzednie lub wcisniecia klawisza RESET na stacji dyskow.

 Operacje dokonywane na plikach CP/M lub TOS sa wywolywane
symetrycznie z klawiszem CONTROL w TIMEX TERMINAL 3000
(EXTENDE─MODE w ZX SPECTRUM lub rownoczesnie Symbol Shift
i Caps shift w ZX SPECTRUM lub TIMEX 2048) nacisniecie
np. klawisza ^D spowoduje wyswietlenie katalogu dyskietki w
napedzie DOS a bez klawisza CONTROL - wyswietlenie katalogu
dyskietki w napedzie CP/M.

 Program obsluguje 4 napedy (A-D) kazdy z nich mozna 
zadeklarowac jako naped CP/M lub DOS. Obsluga plikow CP/M
jest zrealizowana przez odwolania do systemu natomiast
pozostale funkcje sa obslugiwanie przez program.

 Program zostal napisany w asemblerze (67 KB tekstu
zrodlowego) i skompilowany za pomoca kompilatora GEN80 firmy
HiSoft.

Lublin, dn.1991.06.27
