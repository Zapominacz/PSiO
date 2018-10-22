# Lab 4
#### Tablice i kolekcje

### Zad 1
Wykorzystując klasę [Random](https://docs.oracle.com/javase/8/docs/api/java/util/Random.html) należy wygenerować tablicę 100 liczb całkowitych. Następnie należy wyliczyć i wypisać na ekranie średnią i [odchylenie standardowe](http://matematyka.pisz.pl/strona/1028.html). Utworzyć klasę do przechowywania tych dwóch wartości.

### Zad 2
Utworzyć dwie tablice liczb zmiennoprzecinkowych, następnie należy do pierwszej z nich dodać połowę elementów z drugiej tablicy. Kolejnym etapem jest usunięcie 30 elementów z początku tablicy. Pozostałe elementy należy zamienić kolejnością tak, aby pierwszy element wymienił się z ostatnim, drugi pozostał bez zmian, trzeci wymienił z przed-przedostatnim, itd...

(*) Wykonać zadanie w dodatkowy sposób przy pomocy `System.arraycopy`.

### Zad 3
Napisać funkcję, która wykonuje [mnożenie macierzy](http://matematykadlastudenta.pl/strona/395.html). Jako argumenty przyjmuje dwie macierze (tablice dwuwymiarowe), a jako rezultat zwraca wynikową macierz. Obsłużyć w wybrany sposób przypadki niezgodności wymiarów macierzy. Napisać funkcję do wyświetlania na ekranie macierzy.

### Zad 4
Zrealizować **zad 1** i **zad 2** (bez *) przy pomocy [ArrayList](https://docs.oracle.com/javase/8/docs/api/java/util/ArrayList.html). Jakie różnice zauważasz?

### Zad 5
Napisać funkcję, która wylicza [Odległość Hamminga](https://pl.wikipedia.org/wiki/Odleg%C5%82o%C5%9B%C4%87_Hamminga) między dwoma łańcuchami znakowymi `String` podanymi jako argument. Warto zajrzeć do [dokumentacji klasy String](https://docs.oracle.com/javase/8/docs/api/java/lang/String.html). Zakładamy, że wszystkie znaki są zapisane małymi literami (metoda `String.toLowerCase()` zamienia wszystkie znaki na małe). Metoda `String.charAt(int index)` umożliwia pobranie danego znaku z łańcucha o długości `String.lenght()`.