# Lista zadań PSiO 1
Wprowadzenie do środowiska Eclipse
Termin: 09.10.18

## Cel
* Zapoznać się ze środowiskiem Eclipse
* Uruchomić pierwszy program
* Napisać pierwszy program

## Materiały
* [Eclipse IDE](https://www.eclipse.org/downloads/packages/release/2018-09/r/eclipse-ide-java-developers) - wymagany dla pierwszych dwóch zadań oraz używany na wykładzie.
* [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) - uznany edytor dla języka Java. **Ciekawostka:** aktywując konto mailem studenckim dostaje się za darmo dostęp do wersji płatnych edytora.
* [Codecademy](https://www.codecademy.com/learn/learn-java) - Strona z przystępnym kursem języka Java, w internecie znajduje się ich masa. Elementy darmowe kursu wystarczają do poznania podstaw języka, natomiast płatne nie wnoszą nic poza dodatkowymi ćwiczeniami.

# Zadania

## Zadanie 1 - Utworzenie, uruchomienie i eksport projektu.
**Uwaga:** zadanie można wykonać w różne sposoby.

1. Uruchom (zainstaluj, gdy niezainstalowany) Eclipse IDE.
2. Wybierz z przybornika *New* (ikonka okienka) -> *Java* -> *Java Project*. Jako nazwa projektu wpisać `HelloWorld` i nacisnąć finish.
4. Wybrać PPM na nowo utworoznym projekcie w oknie *Package explorer* i wybrać *New* -> *Class*. Jako nazwę wpisać HelloWorld, **zaznaczyć public static void main(String[] args)** i nacisnąć finish.
5. Zapisać komendę `System.out.println();` do wyświetlania danych na terminalu, jako argument podać swoje imię i nazwisko np. `"Jan Kowalski"`. Zapisać plik.

Doskonale, właśnie został utworzony pierwszy program (i projekt).

6. Wybrać plik *HelloWorld.java* w *Package explorer*, wybrać *Run as* -> *Java Application*.
7. W okienku na dole edytora powinno pojawić się Twoje imię i nazwisko.

Etap pierwszego uruchomienia został zrealizowany, na sam koniec projekt eksportujemy (np. aby wysłać na swojego maila).

8. Ponownie wybrać projekt PPM i wybrac opcje *Export* -> *General* -> *Archive file*. Podać ścieżkę do utworzenia archiwum i nacisnąć *Finish*.

## Zadanie 2 - Import projektu.
Teraz należy pobrać projekt, na którym zostanie wykonane trzecie zadanie. Projekt można pobrać [TUTAJ](https://github.com/Zapominacz/PSiO/raw/master/lab_1/projekt.zip).

Pobrany projekt należy zaimportować poprzez wybranie na pasku narzędziowym opcji *File* -> *Import* -> *General* -> *Existing project into workspace* oraz wybrać ścieżkę pobranego projektu (Archive file) w formacie *.zip* .

Doskonale, opanowany został import projektów.

Kolejnym etapem jest użycie debuggera. W tym celu należy nacisnąć dwukrotnie na numer linii 41 i uruchomić debugger przyciskiem z "robaczkiem". Jakie zmienne widzisz w oknie *Variables*? 

## Zadanie 3 - Zadanie.
Ostatnim zadaniem jest wypełnienie dwóch funkcji w zaimportowanym w 2 zadaniu projekcie: `power(int a, int b)` oraz `fooBar()`.