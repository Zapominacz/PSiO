# Lab 5 - Klasy i relacje
**Po ocenie zadania przez prowadzącego proszę przesyłać je na adres mailowy mikolaj.stys@pwr.edu.pl**

## Zadanie
Utwórz własny projekt, który będzie przedstawiał dowolny wybrany przez Ciebie wycinek rzeczywistości. Projekt:
- Zawiera 1 klasę abstrakcyjna
- Zawiera 2 relacje typu „MA” (agregacja), przy czym przynajmniej jedna korzysta z tablicy lub listy.
- Zawiera 2 relacje typu „JEST” (dziedziczenie)
- Stosuje zasadę hermetyzacji, zawiera metody dostępowe **get** i **set**
- Wykorzystuje **przesłonięcia** metod (czyli korzysta z polimorfizmu)
- Wykorzystuje **przeciążenia** metod
- Zawiera przesłaniającą metodę, która odwołuje się do metody przesłoniętej
- Wykorzystuje w konstruktorze odwołanie do konstruktora klasy nadrzędnej
- Wykorzystuje w konstruktorze odwołanie do innego konstruktora danej klasy
- Tworzy przykładową instancję opisanego wycinka rzeczywistości (utworzyć obiekty danych klas)
- Posiada dwie interakcje między obiektami (czyli zawiera metodę, która jako argument przyjmuje inny obiekt, czego rezultatem jest zmiana stanu jednego z obiektów)

Klasy posiadają nadpisane metody toString(), dzięki czemu można określić stan i relacje z innymi obiektami (np. Pies[Azor, Obroża[Niebieska]])

Wskazane jest, by projekt nie dotyczył psów :)
