# Lab 8
Metody i klasy generyczne. Porównywanie obiektów.

## Zad 1 (25 pkt)
Dodaj do swojego projektu klasę generyczną. Klasa ta powinna mieć przynajmniej jedno pole i jedną metodę powiazaną z typem generycznym.

Pomysł: klasa przyjmująca obiekt do zapisu (np. obiekt klasy Kot lub Pies), a następnie zapisująca go.

## Zad 2 (15 pkt)
Dodaj do swojego projektu metodę generyczną.

Pomysł: metoda do wyświetlania obiektów wykonującą dodatkowe formatowanie (np. wyświetlanie indeksów obiektów w tablicy).

## Zad 3 (30 pkt)
Przy pomocy przesłonięcia metod `equals` i `hashCode` określ kiedy dwa obiekty są identyczne (dla wszystkich Twoich klas w projekcie). Podczas importowania obiektów z pliku lub dodawania obiektu samodzielnie należy zduplikowany obiekt pominąć i wyświetlić o tym komunikat.

Uwaga: jeżeli Twój projekt zawiera wielokrotnie zagnieżdżone struktury, aktualnie przy zapisie można określić pewne założenia dotyczące struktury zapisywanych obiektów.

Utwórz metodę generyczną do porównywania tablic/list obiektów (nie musi być użyta w projekcie).

## Zad 4 (20 pkt)
Wykorzystaj interfejs  oraz `Comparable ` w celu sortowania obiektów w Twojej aplikacji. Powinna być to nowa funkcjonalność w “menu” utworzonym na laboratoriach nr 6.

## Zad 5 (10 pkt)
Wykorzystaj interfejs `Comparator` w celu wykonania poprzedniego zadania. Czym różni się się `Comparator` od `Comparable`?