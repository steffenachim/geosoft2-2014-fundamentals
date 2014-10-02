
Relationale Datenbanken
---
**Allgemeines:**

Die relationale Datenbank ist die am weitesten verbreitete Form der Datenbanksysteme. 8 der 10 meistgenutzten Datenbanken basieren darauf. Dementsprechend gibt es eine intensive Weiterentwicklung und laufende Verbesserungen, auch dank großer Firmen wie Oracle und Microsoft. Die am häufigsten benutzten OpenSource Datenbanken sind MySQL und PostgreSQL.

**Aufbau:**

Diese Datenbanken basieren auf Tabellen (Relationen). Die Spalten enthalten dabei die Attribute und sind fest definiert durch ein Relationschemata. Die Zeilen bestehen aus den einzelnen Datensätzen und können dynamisch verändert werden.

**Vorteile / Nachteile:**

Vor allem für viele einfache Operationen/Zugriffe eignet sich diese Form der Datenbanken. Datenintegrität und Datenkonsistenz sind immer gesichert. Allerdings gibt es bei sehr komplexen Zugriffen, wo mehrere Relationen auf einmal betrachtet werden müssen, aufgrund der Struktur Leistungsabfälle. Zudem fehlt es an Dynamik, da das Relationschemata einmal festgelegt wird und danach nicht flexibel geändert werden kann.


NoSQL
---
**Allgemeines:**

NoSQL bedeutet 'Not only SQL'. Es behandelt Datenbanken welche nicht auf eine herkömmliche Architektur basieren, sondern auf eine welche dynamisch und erweiterbar ist. D.h. es herrscht keine festes Schema. Die Entwicklung dieser Datenbanken ist meist auf den jeweiligen Anwendungsfall zugeschnitten. Daher gibt es viele sehr unterschiedliche NoSQL Datenbanktypen. Früher gab es lange nur SQL Datenbanken, aber seit ein paar Jahren werden diese immer beliebter. Firmen wie zum Beispiel Facebook entwickeln diese.

**Beispiel CouchDB:**

Diese Form ist eine Dokumentorientierte Datenbank, was bedeutet, dass eine Speicherung unstrukturierter Daten mit flexibler Attributewahl Praxis ist. Dies ist vor allem positiv für die Skalierbarkeit und den Austausch zwischen Off-/Online Daten.

**Beispiel Neo4J:**

Diese Graphen-Datenbanken bestehen nur aus Knoten, Beziehungen und den dazugehörigen Attributen. Daher eignet sich diese Art der NoSQL Datenbanken besonders gut für die Umsetzung komplexer Beziehungen zwischen Relationen. Auch hier gibt es wieder eine große Flexibilität.

**Vorteile / Nachteile:**

NoSQL Datenbanken verzichten größtenteils auf eine zu jedem Zeitpunkt garantierte Datenkonsistenz, erlauben dadurch aber eine wesentlich größere Dynamik. Je nach Projektanforderungen, sind sie eine ernsthafte Alternative zu herkömmlichen Datenbanken.



Quellen:
---
Relationale Datenbank:
http://de.wikipedia.org/wiki/Datei:Begriffe_relationaler_Datenbanken.svg
http://db-engines.com/de/ranking
http://www2.pmf.fh-goettingen.de/~jwitte/lehre/Medieninformatik/Datenbanken/Vorlesungskripte/Das%20Relationenmodell.pdf

NoSQL: 
http://www.heise.de/open/artikel/NoSQL-im-Ueberblick-1012483.html?artikelseite=2
http://de.wikipedia.org/wiki/NoSQL
http://www.nosqldatabases.com/main/tag/neo4j
http://www.nosqldatabases.com/main/2010/8/5/san-diego-nosql-meetup-slides.html
