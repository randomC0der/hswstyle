# Dokumentation zu hswstyle

## Bibliografieren: Benötige Angaben

Es gibt unterschiedliche Arten von Quellen, die auch entsprechend unterschiedlich zitiert werden müssen.
Diese wurden wie folgt in ``LaTeX`` umgesetzt:

* Monographien → ``@book``
* Sammelwerkbeiträge → ``@incollection``
* Zeitschriftenartikel → ``@article``
* Internetquellen → ``@online``
* Öffentliche betriebliche Quellen → ``@report``

Damit die Einträge richtig generiert werden können, müssen folgende Angaben gegeben sein. In Klammern steht der Typ, der die Angabe benötigt.

* ``author``: Die Verfasser des Textes. Format: Vorname Nachname. Teile, die genau so ausgegeben werden sollen, weil beispielsweise der Name Leerzeichen enthält, werden mit ``{}`` oder ``""`` eingerahmt. Mehrere werden mit ``and`` abgetrennt (``@book, @incollection, @article, @online, @report``)
* ``year``: Veröffentlichungsjahr (``@book, @incollection, @article, @online, @report``)
* ``title``: Name der Publikation (``@book, @incollection, @article, @online, @report``)
* ``publisher``: Name des Verlags (``@book, @incollection``)
* ``edition``: Nummer der Auflage (``@book, @incollection``)
* ``pages``: Seiten, auf denen die Quelle steht (``@incollection, @article``)
* ``editor``: Name der Herausgeber. Mehrere werden mit ``and`` abgetrennt (``@incollection``)
* ``booktitle``: Name des Sammelwerkes (``@incollection``)
* ``journaltitle``: Name der Zeitschrift (``@article``)
* ``number``: Heftnummer/Ausgabe der Zeitschrift (``@article``)
* ``volume``: Jahrgang der Zeitschrift (``@article``)
* ``url``: Link zur Internetseite (``@online``)
* ``urldate``: Datum, an dem die Seite aufgerufen wurde. Format yyyy-mm-dd (``@online``)
