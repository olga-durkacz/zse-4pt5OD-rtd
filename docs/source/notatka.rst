Notatka z reStructuredText
===========================


Nagłówki
---------
| ``Nagłówek h1``

``===========``

| ``Nagłówek h2``

``------------``

| ``Nagłówek h3``

``~~~~~~~~~~~``

| ``Nagłówek h4``

``^^^^^^^^^^^``



Akapit tekstowy
---------------
Tekst (nie trzeba dodać żadnych spe-cjalnych znaków). By tworzyć nowe akapity trzeba odzielić tekst jednyną pustą linią. 



Akapit informacyjny - Note
--------------------------
| ``.. note::``

``________Jakaś notka``

.. note::
     W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie



Akapit informacyjny - Tip
-------------------------
| ``.. tip::``

``________Jakaś wskazówka``

.. tip::
      W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie    



Fragment kodu - liniowy
-----------------------
Fragment kodu oznaczamy `` na końcu i napoczątku frazy. Nie wolno dać spacji pomiędzy `` a wrazami.
````kod````



Fragment kodu - blokowy
-----------------------
| ``..  code-block:: txt``

| ``___:caption: podpis fragmentu kosu``

| ``(Puta linjka przerwy)``

``___<kod>``

  W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie
 


Odnośnik wewnętrzny (w obrębie dokumentacji)
---------------------------------------------
``:ref:`ważne rzeczy tu <nazwa i lokacja podstrony w dokumencie>```



Odnośnik zewnętrzny (do innego serwisu)
---------------------------------------
```Tekst z linkiem <https://przykladowylink>`_``



Lista numerowana
----------------
| ``1. Punkt1``

``2. Punkt2``

``#. Punkt3 (którego numer wygeneruje się automatycznie)``



Lista wypunktowana
------------------
| ``* Punkt1``

| ``* Punkt2``

``* Punkt3 (do oznaczenia listy można użyć *,+,-)``



Lista definicji
---------------
| ``Nazwa1``

``_______Definicja rzeczy1``

| ``Nazwa2``

``_______Definicja rzeczy2``

| ``Nazwa3``

``_______Definicja rzeczy3``

  W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie



Obraz - ścieżka
---------------
| ``.. figure:: /_static/images/img.png``

| ``___:alt: To co jest na obrazku``

| ``(pusta linka co odziela)``

``___Napis pod obrazkiem``

  W miejsce "____" wstaw spacje, są podane one tutaj jako wypełnienie



Tabela z danymi
-----------------

| ``+-----------+-----------+``

| ``| Header 1  | Header 2  |``

| ``+===========+===========+``

| ``| column 1  | column 2  |``

| ``+-----------+-----------+``

| ``| Cells may span        |``

``+-----------------------+``
