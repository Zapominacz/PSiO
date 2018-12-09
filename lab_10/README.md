# Lab 10 - GUI, obsługa błędów
**Termin oddania listy: 08.01.2018**

## Zad 1 (100 pkt)
Wykonać dla swojego projektu interfejs graficzny, który pełni analogiczną rolę do wcześniej zaimplementowanego interfejsu tekstowego.  Interfejs musi:
* Posiadać przyciski do import / eksportu obiektów
* Zawierać listę obiektów
* Posiadać osobne okienko do podglądu (i edycji) pojedynczego obiektu
* Umożliwiać utworzenie nowego obiektu
* Umożliwiać zamknięcie aplikacji wraz z potwierdzeniem wyjścia z aplikacji
* Dla ograniczonych wartości zawierać suwaki lub tzw. combo box’y
* Wykorzystać co najmniej jedną grafikę
* Umożliwiać sortowanie obiektów
* Daje możliwość filtrowania obiektów
* Zawiera przycisk do automatycznego generowania nowego obiektu z losowymi danymi.

**Uwaga:** interfejs ma zostać napisany samodzielnie, bez użycia generatorów GUI.

## Zad 2 (40 pkt)
Wykorzystać system obsługi błędów `try - catch - finally` do obsługi błędów w swoim projekcie.  Minimalnie, projekt:
* Ma informować uzytkownika o niepoprawnej wartości i czekać na poprawną.
* Obsługiwać błędy związane z wartościami `null`
* Obsługiwać błędy związane z wejściem - wyjściem, tj.
	* Odczyt plików
	* Zapis plików
	* Nadpisywanie plików
* Użytkownik powinien dostać zrozumiałą dla niego interpretację błędu.
* Umożliwiać dalszą pracę po napotkaniu powyższych problemów (tzn nie przerywać wykonywanego przez użytkownika zadania).
* W projekcie należy także zgłaszać własne wyjątki, które są przechwytywane przez interfejs graficzny i obsługiwane.
* W projekcie nie powinno być obsługi błędów przez wartości logiczne, kod błędu lub zwracanie wartości `null` (jeżeli nie jest to uzasadnione).

Oprócz tego należy wykorzystać w programie asercje do weryfikacji stanu programu (min. 4 użycia).

## Zad 3 (60 pkt)
*(zadanie moze być wykonane poza głównym projektem)*
Należy zaimplementować dowolny [L-system](https://pl.wikipedia.org/wiki/L-system), który rysuje w okienku programu jego graficzny twór o zadanych parametrach.

**Zadania proszę wysłać po sprawdzeniu na mail: mikolaj.stys@pwr.edu.pl**