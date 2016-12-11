## Nazwa: Baza teatru (Technologia JDBC) 
# Termin oddania : 24.12.2016
# Opis: Tabele aktor i przedstawienie oraz tabela występ jako pośrednicząca w relacji n:m
 Wymagania odnośnie projektu

Oczywiście system kontroli wersji - należy go prowadzić !_SYSTEMATYCZNIE_!

Projekt powinien zawierać:

    co najmniej jeden pełny CRUD
    
    Powinny być co najmniej 3 pola w jednej tabeli bazy danych.
    
    zaimplementowaną relację
    
    testy jednostkowe do istotnych części projektu (czyli CRUD, obsługa relacji)
    
        należy umieć pokazać testy w terminalu i wiedzieć gdzie lądują logi 
        
    zabronione nazwy pól to (case insensitive):
    
        yob, nazwisko 

uwaga odnośnie relacji

Niech będzie relacja jeden (y) do wielu (x), albo wiele do wielu. Powinny być metody:

    pobranie x należących do y
    
    pobranie wszystkich y
    
    przypisanie x do y
    
    usunięcie x z y
    
    dodanie do tabeli x, dodanie do tabeli y
    
    jeśli jakaś czynność wymaga kilku operacji na bazie danych, wtedy powinno to być wykonane w jednej transakcji.
    
    oczywiście testy do wszystkiego. Testy powinny być (o ile to możliwe) niezależne od tego, czy w bazie na początku
    testu już coś jest, czy też nie. 
    Jeśli potrafisz, to zastosuj klucze obce. 




