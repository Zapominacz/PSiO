# Lab 12 - MVC
**Termin oddania listy: 29.01.2018**

Wykonaj refaktor projektu (25 pkt). W projekcie powinny znaleźć się elementy architektury MVC (lub innej, jeżeli zostanie to ustalone z prowadzącym), tj.
* *Model*, czyli klasy zawierające dane przesyłane między warstwami architektonicznymi aplikacji (przykładem jest klasa Pies - zawiera dane o psie, które są importowane z pliku a następnie wyświetlane w interfejsie graficznym (25 pkt).
* *View (widok)*, czyli zestaw klas odpowiadających za wyświetlenie danych na ekranie przy pomocy odebranych modeli (przykładem są klasy tworzące interfejs graficzny listy, która wyświetla dane o psach, poprzednio odebranych w formacie listy obiektów klasy Pies) (25 pkt).
* *Controller (kontroler)*, czyli zestaw klas odpowiadających za zarządzanie pewną logiką aplikacji (przykładem może być klasa która importuje lub eksportuje dane do pliku, i przesyłająca rezultaty do klas odpowiadających za widok) (25 pkt).

Modeli, widoków oraz kontrolerów może być wiele i mogą tworzyć strukturę hierarchiczną (model Psa zawiera model Obroży, widok listy Psów zawiera widok pojedynczego Psa, kontroler zarządzający widokiem listy Psów w aplikacji zawiera kontroler do importowania, eksportowania listy modeIi) .

**Uwaga:** W liście będzie oceniany cały projekt, który był tworzony podczas zajęć laboratoryjnych oraz zadanie. Osoby, które uznały, że otrzymały wystarczającą liczbę punktów dla wybranej oceny mogą nie wykonywać żadnych zmian w projekcie i nie robić zadania. Projekt oraz dotychczasowe punkty będą podstawą do oceny, przy czym projekt może jedynie poprawić ocenę na lepszą.