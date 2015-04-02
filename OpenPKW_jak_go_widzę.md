#openPKW

Cały system powinien składać się z 2 głównych modułów/działów/zadań:

# A. Platforma Wyborcza  
# B. Kalkulator wyborczy  

Kolejne podziały powinny wynikać z potrzeb organów wyborczych wszystkich szczebli i rodzajów oraz z funkcjonalności oprogramowania i baz danych wykorzystywanych w procesie przygotowania i przeprowadzenia wyborów oraz agregacji i ogłoszenia wyników wyborów.


# Ad. A.
* A.1. zbieranie i przetwarzanie danych przed wyborczych zgodnie z przedstawionym graficznie (draw.io) procesem. (/// link po umieszczeniu grafiki draw.io na githubie)
* A.2. odebranie danych w noc wyborczą z komisji obwodowych, przetworzenie i przygotowanie do pobrania przez komisje wyborcze wyższego rzędu, przyjęcie danych z komisji wyższego rzędu, przetworzenie i przygotowanie danych dla PKW.
* A.3. wizualizacja bieżącej akcji wyborczej
* A.4. stały dostęp do danych archiwalnych (zakończone akcje wyborcze i ich wizualizacje)

# Ad. B.

* B.1. program do instalacji lokalnej (np. maszyny bez dostępu do internetu itp.)
* B.2. strona HTML (rozbudowany obecny prototyp kalkulatora w html) frontend?  
oba punkty zgodne z przedstawionym graficznie (draw.io) [procesem] (https://www.draw.io/?url=https%3A%2F%2Fraw.githubusercontent.com%2Fopenpkw%2Fopenpkw%2Fmaster%2Fdokumentacja%2Fprocesy%2FObwodowa%2520komisja%2520wyborcza.xml)  

i na nieco innych zasadach:  

* B.3. oprogramowanie mobilne (np. wykorzystywane przez różnorodne organizacje do sprawdzania poprawności wyborów)

# Ad. B.1. 

* B.1.1. oprogramowanie dla local host zgodne z [propozycją funkcjonalności] (https://github.com/openpkw/openpkw/blob/master/dokumentacja/oper_kalkulator.md)
* B.1.2. oprogramowanie serwerowe
     * B.1.2.1. odbiór danych w noc wyborczą z Komisji Wyborczych
     * B.1.2.3. przetworzenie danych wyborczych i udostępnienie ich do dalszej pracy komisjom wyższego rzędu
     * B.1.2.3. prztworzenie danych wyborczych i udostępnienie ich do A.2. Platforma Wyborcza.

# Ad. B2.

* B.2.1. odbiór danych w noc wyborczą z Komisji Wyborczych. (symultanicznie z B.1.2.1.)
 
# Ad.B3.

* B.3.1. program mobilny (co najmniej Android i IOS) umożliwiający szybkie przekazanie cześci danych liczbowych z protokołu.
    * B.3.1.1. implementacja możliwości przesłania danych SMS ze starszych modeli telefonów.
* B.3.2. oprogramowanie serwerowe 
    * przetworzenie danych, ich agregacja i udostępnienie danych zbiorczych/wizualizacja.

