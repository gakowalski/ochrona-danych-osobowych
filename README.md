# Ochrona Danych Osobowych

## O repozytorium

W tym repozytorium przeprowadzam moje własne przekształcenia aktów prawnych związanych z ochroną danych osobowych do bardziej przyjaznej w obsłudzie postaci. Ponżej lista przetwarzanych, przetworzonych i planowanych do przetworzenia.

## Akty prawne

* RODO - [wersja pełna](http://grzegorzkowalski.pl/ochrona-danych-osobowych/rodo.php), [wersja skrócona](http://grzegorzkowalski.pl/ochrona-danych-osobowych/rodo.php?short=1), jeszcze nie wszystko hyperlinkowane, pracuję powoli
* UODO 2018, (w planach)
* DODO, (w planach)
* KRI, (w planach)

## Co w nich zmieniam?

### Hiperlinki

Odwołania do innych aktów prawnych zamieniam na hiperlinki, czyli zamiast tekstu:

> Celem dyrektywy Parlamentu Europejskiego i Rady 95/46/WE (1) jest zharmonizowanie ochrony

Może się pojawić:

> Celem [dyrektywy Parlamentu Europejskiego i Rady 95/46/WE](https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=OJ:L:1995:281:TOC) jest zharmonizowanie ochrony

Co, więcej, po najechaniu kursorem na taki link i przytrzymaniu, pojawi sie podpowiedź z pełnym tytułem aktu prawnego.

### Wersja skrócona

Uruchomienie tekstu aktu prawnego z parametrem `short=1` w adresie URL uruchamia wersję skróconą, w której długie nazwy linków ulegają skróceniu, ale zachowują podpowiedź po najechaniu myszą i wciąż prowadzą tam gdzie powinny. Czyli to:

> Celem [dyrektywy Parlamentu Europejskiego i Rady 95/46/WE](https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=OJ:L:1995:281:TOC) jest zharmonizowanie ochrony

Zamieni się w:

> Celem [95/46/WE](https://eur-lex.europa.eu/legal-content/PL/TXT/?uri=OJ:L:1995:281:TOC) jest zharmonizowanie ochrony

Poza tym, prawie wszystkie odwołania do "niniejszego rozporządzenia" zostają zastąpione tekstem "RODO" a odwołania do "inspektora ochrony danych" zastąpione skrótem "IOD". Czyli to:

> Profilowanie podlega przepisom niniejszego rozporządzenia dotyczącym przetwarzania danych osobowych

Zamieni się w to:

> Profilowanie podlega przepisom RODO dotyczącym przetwarzania danych osobowych

### W planach

* dodać możliwość łatwego podglądu treści artykułów, ustępów i punków, do których odnosi się dany przepis, np. najeżdzamy myszą na "Art. 6 ust. 1 lit b)" i w dymku pojawia się jego treść - ograniczy to scrollowanie po całym dokumencie;
* dodać możliwość szybkiego podglądu, które artykuły istotnie modyfikują postanowienia danego przepisu;
* dodać możliwość szybkiego przełączenia między motywami a powiązanymi z nimi artykułami;
* przemyśleć jak to mogłoby działać na urządzeniach mobilnych.
