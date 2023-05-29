# FSE_LAND_Makroarchitektur

## Theorie: Recherchiere zu folgenden Fragestellungen und fasse deine Erkenntnisse übersichtlich und illustrativ zusammen!

#
### Was ist Sofwarearchitektur?
Die Dokumentation der Softwarearchitektur ist von großer Bedeutung, um das Verständnis, die Kommunikation und die Weiterentwicklung der Software zu erleichtern. Es gibt verschiedene Methoden und Werkzeuge, die für die Dokumentation der Softwarearchitektur verwendet werden können. Hier sind einige gängige Ansätze:

-   Architekturbeschreibungen: Schriftliche Beschreibungen sind eine der grundlegenden Möglichkeiten, um die Softwarearchitektur zu dokumentieren. Es können Textdokumente erstellt werden, die die Architekturprinzipien, die Funktionalitäten der verschiedenen Komponenten, die Interaktionen zwischen den Komponenten und andere relevante Informationen erklären.

-   UML-Diagramme: Die Unified Modeling Language (UML) bietet eine Reihe von Diagrammtypen, die verwendet werden können, um die Softwarearchitektur zu visualisieren. Dazu gehören Klassendiagramme, Sequenzdiagramme, Paketdiagramme, Aktivitätsdiagramme usw. Diese Diagramme können die Struktur, die Beziehungen und das Verhalten der Komponenten veranschaulichen.

-   Architektur-Canvas: Ein Architektur-Canvas ist ein visuelles Modell, das eine Zusammenfassung der wichtigsten Architekturaspekte bietet. Es enthält Felder oder Abschnitte, in denen Informationen zu den Hauptkomponenten, den Interaktionen zwischen ihnen, den Schnittstellen, den Datenflüssen und den Designentscheidungen festgehalten werden können.

-   Code-Kommentare: Eine andere Möglichkeit, die Softwarearchitektur zu dokumentieren, besteht darin, Kommentare im Quellcode zu verwenden. Dies ermöglicht es den Entwicklern, wichtige Designentscheidungen, Abhängigkeiten zwischen Modulen und andere relevante Informationen direkt im Code zu erfassen.

Es ist wichtig, eine angemessene Balance zwischen detaillierter Dokumentation und leicht verständlichen Informationen zu finden. Die gewählte Methode hängt von den Anforderungen des Projekts, der Zielgruppe und den Präferenzen des Entwicklungsteams ab. Oftmals wird eine Kombination verschiedener Ansätze verwendet, um ein umfassendes Bild der Softwarearchitektur zu vermitteln.

#
### Wie kann man Softwarearchitektur dokumentieren?
Die Dokumentation der Softwarearchitektur kann auf verschiedene Weisen erfolgen. Hier sind einige Ansätze zur Dokumentation der Softwarearchitektur:

-   Architekturbeschreibungen: Verfassen Sie schriftliche Beschreibungen, um die Softwarearchitektur zu dokumentieren. Dies kann in Form von Textdokumenten, Architekturübersichten oder Architekturbeschreibungen erfolgen. Beschreiben Sie die grundlegenden Konzepte, Komponenten, deren Funktionen und Beziehungen zueinander.

-   Diagramme: Verwenden Sie visuelle Diagramme, um die Softwarearchitektur zu veranschaulichen. UML-Diagramme (Unified Modeling Language) wie Klassendiagramme, Komponentendiagramme, Sequenzdiagramme und Aktivitätsdiagramme sind gängige Methoden, um die Struktur, Interaktionen und Abläufe der Softwarearchitektur darzustellen.

-   Architekturmodelle: Erstellen Sie Modelle, die die Softwarearchitektur auf abstrakterer Ebene beschreiben. Architekturmodelle können verschiedene Perspektiven wie Logikschicht, Datenflüsse, Komponenteninteraktionen und Datenstrukturen umfassen. Sie dienen dazu, das Verständnis der Architektur zu erleichtern und Entscheidungen zu unterstützen.

-   Prototypen und Proof-of-Concepts: Erstellen Sie funktionierende Prototypen oder Proof-of-Concepts, um die Softwarearchitektur zu veranschaulichen und wichtige Aspekte zu demonstrieren. Dies kann dazu beitragen, das Verständnis der Architektur zu verbessern und potenzielle Herausforderungen frühzeitig zu erkennen.

-   Dokumentationstools: Nutzen Sie spezialisierte Tools oder Softwarearchitektur-Frameworks, die eine strukturierte Dokumentation ermöglichen. Diese Tools bieten oft vorgefertigte Vorlagen, um Diagramme zu erstellen, und unterstützen die Zusammenarbeit im Team.

-   Inline-Kommentare: Fügen Sie innerhalb des Quellcodes der Softwarearchitektur relevante Inline-Kommentare hinzu. Diese Kommentare können wichtige Entscheidungen, Abhängigkeiten oder Designprinzipien erläutern und das Verständnis der Architektur beim Lesen des Codes verbessern.

Es ist wichtig, dass die Dokumentation kontinuierlich aktualisiert und gepflegt wird, um den Entwicklern und Stakeholdern stets eine aktuelle und verständliche Übersicht über die Softwarearchitektur zu bieten.

#
### Welches sind die wichtigsten Eigenschaften von Langlebigen Softwarearchitekturen (Lilienthal)
Carola Lilienthal hat in ihrem Buch "Langlebige Softwarearchitekturen" einige wichtige Eigenschaften von Softwarearchitekturen identifiziert, die zu ihrer Langlebigkeit beitragen können. Hier sind einige dieser Eigenschaften:

-   Modularität: Eine langlebige Softwarearchitektur ist modular aufgebaut, sodass einzelne Komponenten unabhängig voneinander entwickelt, getestet und gewartet werden können. Dies ermöglicht eine hohe Flexibilität und erleichtert Änderungen in der Software.

-   Klare Abstraktionen: Die Architektur sollte klare Abstraktionen verwenden, um komplexe Systeme in überschaubare Module zu unterteilen. Dadurch wird die Komplexität reduziert und das Verständnis der Architektur erleichtert.

-   Lose Kopplung: Eine langlebige Softwarearchitektur zeichnet sich durch eine geringe Kopplung zwischen den einzelnen Komponenten aus. Dadurch können Änderungen in einer Komponente durchgeführt werden, ohne dass dies große Auswirkungen auf andere Teile des Systems hat.

-   Hohe Kohäsion: Die Komponenten einer langlebigen Softwarearchitektur sollten stark zusammengehörige Funktionen bündeln. Dadurch wird die Lesbarkeit, Wartbarkeit und Testbarkeit verbessert.

-   Erweiterbarkeit: Eine langlebige Softwarearchitektur sollte es ermöglichen, das System einfach zu erweitern, um neue Anforderungen zu erfüllen. Dies kann durch den Einsatz von Schnittstellen und Erweiterungspunkten erreicht werden.

-   Testbarkeit: Eine gute Testbarkeit ist eine wichtige Eigenschaft von langlebigen Softwarearchitekturen. Durch klare Abgrenzungen zwischen den Modulen und die Verwendung von automatisierten Tests kann die Stabilität und Qualität des Systems gewährleistet werden.

-   Dokumentation: Eine umfassende und aktuelle Dokumentation ist entscheidend, um das Verständnis der Softwarearchitektur langfristig aufrechtzuerhalten. Die Dokumentation sollte sowohl die Designentscheidungen als auch die Schnittstellen und Abhängigkeiten des Systems umfassen.

Diese Eigenschaften tragen dazu bei, dass eine Softwarearchitektur langlebig ist und Änderungen und Weiterentwicklungen effizient und nachhaltig unterstützt.

#
### Was ist ein Modulith?
Ein Modulith ist ein Begriff, der in der Softwarearchitektur verwendet wird und eine spezielle Art von Softwaremodul beschreibt, das sowohl die Vorteile von monolithischen Architekturen als auch von modular aufgebauten Architekturen kombiniert.

Im Kontext von Softwarearchitektur bezieht sich der Begriff "Modulith" auf eine Monolith-Architektur, bei der die internen Komponenten und Module klar voneinander abgegrenzt und nach bestimmten Designprinzipien organisiert sind. Im Gegensatz zu einer traditionellen monolithischen Architektur, in der alle Funktionen und Komponenten in einem einzigen großen Codebase zusammengefasst sind, ermöglicht der Modulith eine logische Unterteilung des Codes in mehrere Module.

Ein Modulith verwendet oft Module oder Domänen als organisatorische Einheiten, um verwandte Funktionen und Verantwortlichkeiten zusammenzufassen. Diese Module können intern weitere Untermodule oder Komponenten enthalten. Jedes Modul ist jedoch Teil eines einzigen, integrierten Builds und wird als zusammenhängende Einheit bereitgestellt.

Der Modulith-Ansatz ermöglicht es, die Vorteile eines monolithischen Ansatzes beizubehalten, wie z.B. einfacheres Deployment, leichtere Datenzugriffe zwischen Modulen und eine gemeinsame Codebasis. Gleichzeitig erlaubt er eine klarere Trennung von Verantwortlichkeiten und eine bessere Modularität, was die Wartbarkeit und Erweiterbarkeit der Architektur verbessert.

Es ist wichtig anzumerken, dass der Begriff "Modulith" kein allgemein anerkannter Begriff ist und keine einheitliche Definition hat. Die genaue Ausgestaltung eines Moduliths kann je nach Kontext, Anforderungen und Präferenzen variieren.

### Wie funktioniert die Ports and Adapters Architektur?


### DDD: Was sind die wesentlichen Bausteine des modellgetriebenen Entwurfs (Taktische Pattern) aus DDD?


Abgabe der Architekturanalyse des bestehenden erplite-Backends
### Dokumentation (textuelle Beschreibung, Codeauszüge, C4-Diagramme, Klassendiagramme) der Ports-Und-Adapters-Architektur und der DDD-Bestandteile (taktische Muster) von Ordermanagement anhand der gegebenen Anwendungsfälle, die schon implementiert sind:
-   Bestellung aufgeben
-   Bestellung auf bezahlt setzen
-   Packliste generieren
-   Packlistenitems abhaken
-   Bestellung auf IN_DELIVERY setzen wenn alle Packlistenitems gepackt sind
### Dokumentation (textuelle Beschreibung, Codeauszüge, Diagramme, C4-Diagramme, Klassendiagramme) der "Architektur" von Stockmanagement anhand der gegebenen Anwendungsfälle, die schon implementiert sind:
-   Packingliste anlegen
-   Packingitems als verpackt markieren


