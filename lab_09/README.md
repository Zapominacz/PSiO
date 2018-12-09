# Lab9 - Serializacja
## Zad 1 (10 pkt (użycie) + 10 pkt (zapis) + 10 pkt (odczyt))
Zaimplementować zapis i odczyt obiektów przy pomocy `ObjectInputStream` oraz `ObjectOutputStream`. Wczytywanie ma pomijać obiekty istniejące już w programie (sprawdzanie równości obiektów). [Opis serizacji (EN)](https://www.baeldung.com/java-serialization). Zapis/odczyt powinien wspierać zagnieżdżone struktury (tzn. obiekt może mieć jedną lub więcej referencji do innych obiektów) oraz listy obiektów (tzn. możliwość zapisu/odczytu tablicy/listy obiektów).

Wyjaśnić co jest zapisywane i w jaki sposób do pliku.

## Zad 2 (10 pkt (użycie) + 10 pkt (zapis) + 10 pkt (odczyt))
Zaimplementować analogiczny do powyższego zadania zapis i odczyt, jednak w tym przypadku należy wykorzystać format **JSON** lub **XML**. Polecam do tego bibliotekę FasterXML: [GitHub - FasterXML/jackson: Main Portal page for the Jackson project](https://github.com/FasterXML/jackson).

*(Finalna liczba punktów z tego zadania dostosowana będzie do wyników realizacji)*

## Zad 3 (25 pkt)
Opakować stare i nowe rozwiązanie w klasy, które implementują ten sam interfejs (wykorzystanie polimorfizmu dla metod zapisujących i odczytujących obiekty z pliku). 

## Zad 4 (15 pkt)
Wykorzystać w projekcie enumeratory do określania zamkniętych zbiorów wartości (np. płeć: Kobieta, Mężczyzna lub pracownik:  Robotnik, Szef). Jeżeli projekt nie posiada enumeratorów - dodać ich zastosowanie (np. jako argument do wzorca Fabryki).

**Ponownie proszę o przesłanie sprawdzonego zadania na mail:  ** [mikolaj.stys@pwr.edu.pl](mailto:mikolaj.stys@pwr.edu.pl) 