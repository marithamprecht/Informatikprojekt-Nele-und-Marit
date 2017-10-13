# Informatikprojekt-Nele-und-Marit
## Stundenübersicht des Informatikunterichts
[08/09/17, 1. und 2. Stunde](#1)

[13/09/17, 3. Stunde](#2)

[15/09/17, 4. und 5. Stunde](#3)

[20/09/17, 6. Stunde](#4)

[22/09/17, 7. Stunde](#5)

[04/10/17, 8. Stunde](#6)

[06/10/17, 9. und 10. Stunde](#7)

[11/10/17, 11. Stunde](#8)

[13/10/17, 12. und 13. Stunde](#9)



## Erste und zweite Stunde<a name="1"></a> (Doppelstunde)

Zu erst legten wir (Marit und Nele) uns einen Github Account an. Dies war aufwendiger als wir dachten, da das Programm zunächst nicht Nele's E-Mail akzeptierte. Letztlich hat es funktioniert.

Danach haben wir versucht das Programm Greenfoot besser verstehen zu können bzw. kennen zu lernen . Wir brachten dem Wombat bei statt nach links abzubiegen, nach rechts zu laufen, wenn er auf eine Wand trift.



## Dritte Stunde<a name="2"></a>

### Wie setzte ich einen Screenshot und füge ihn in GitHub ein?

Marit konnte aufgrund von Krankheit nicht am Unterricht teilnehmen. 

Deshalb hab ich (Nele) in unserem GitHub-Projekt die Verlinkungen zu den Stunden 1 und 2 hergestellt, und versucht einen Screenshot einzusetzen. Zunächst musste ich heraus finden wie man einen Screenshot macht. Taste: DruckS-Abf. Danach wurde dieser in Paint geöffnet und ausgeschnitten.



## Vierte und fünfte Stunde<a name="3"></a> (Doppelstunde)

Wir haben auf GitHub einen Ordner für Bilder an gelegt und einen Screenshot hochgeladen. Anschließend haben wir gelernt wie man einen Screenshot in ein Projekt einfügt:


![Screenshot01](Bilder/Screenshot01.png "Shot!")

### Greenfootprojekt 

Grundidee:

- Unterwasserwelt

- Delfin, Fisch und Anker

- Delfin ist steuerbar

- Fisch bewegt sich nach Regeln

- Anker fällt vom oberen Spielrand

- Spielziel Delfin isst Fisch, soll alle essen

- trifft Anker Delfin, Spiel Ende

Zuerst haben wir uns den wet-blue Hintergrund für unsere Welt ausgesucht und eingefügt. Sie trägt den Namen "Unterwasserwelt". Danach setzten wir mit der Funktion "new subclass" einen Fisch in unsere Welt. Durch "open editor" konnten wir mit Hilfe von Greenfoot Class Documentation unseren Fisch so programmieren, dass er sich bewegt (move (Anzahl der Schritte)).

![Screenshot01](Bilder/Screenshot02Greenfootspiel.png "Fisch!")


## Sechste Stunde <a name="4"></a>
Diese Stunde wollten wir erreichen, dass sich unser Fisch dreht, wenn er an den Ecken der Welt ankommt.

![Screenshot01](Bilder/Screenshot03GreenfootFischdrehtsich.png "Drehen!")


## Siebte Stunde <a name="5"></a> 
In dieser Stunde war Herr Buhl abwesend. Dennoch arbeiteten wir an unserem Greenfootprojekt weiter.

Zunächst war unser Plan der Stunde den Fisch unbestimmt durch unsere Unterwasserwelt laufen zu lassen. Jedoch stellte sich das ohne helfene Tips, als ziemlich schwierig, wenn nicht sogar als unmöglich herraus, wenn keine Programmiervorkenntnisse existieren. Wir versuchten unser Glück.

Wir programmierten den Fisch so, dass er sich, wenn man Start drückte, um eine bestimmte Gradzahl drehte und danach an der Ecke der Unterwasserwelt, die eingestellten Schritte lief.

Danach hatten wir die Idee einen neuen, gelben Kasten zu öffnen, damit alle eingestellen Funktionen, wie "move","turn(getRandomNumber)" und "atWorldEgde", gleichzeitig ablaufen sollten. 


## Achte Stunde <a name="6"></a>
Da wir Probleme mit der Programmierung unseres eigenen Projektes hatten, haben wir uns dazu entschlossen, uns mit Hilfe eines festgelegten Lernprogramms (Szenario "meet the greeps") ersteinmal einige Grundlagen und Befehle anzueignen. 

### Lernaktivität eins

#### Aufgabe eins:

Der Greep bewegt sich nach rechts und läuft an den Tomaten vorbei.

#### Aufgabe zwei:

Der Greep dreht sich im auf der Stelle.

#### Aufgabe drei:

Der Greep dreht sich im Kreis.

#### Aufgabe vier:

Der Greep bekommt den Befehl sich geradeaus zu bewegen. Sobald er den Rand der Welt erreicht, bekommt er einen anderen Befehl, nämlich sich zu drehen. Sobald diese Bedingung (Greep befindet sich am Rand der Welt) nicht mehr erfüllt wird, bewegt der Greep sich wieder geradeaus.

#### Aufgabe fünf:

Wir fügen eine weitere Bedingung hinzu: Wenn der Greep eine Tomate berührt, so soll er sie entfernen.

### Unser Stand am Ende der Stunde:

![Screenshot01](Bilder/Screenshot.Greepersteschritte.png "Greep!")


## Neunte und zehnte Stunde <a name="7"></a> (Doppelstunde)

#### Aufgabe sechs:

Wir lassen den Greep mithilfe der Pfeiltasten drehen, indem wir unter die "act" Mehode die Befehle "if (Greenfoot.isKeyDown("left"))" und "if (Greenfoot.isKeyDown("right"))" einfügen, und den Greep jeweils um 5, beziehungsweise -5 Grad drehen lassen. 

#### Aufgabe sieben:

Zunächst haben wir wie gefordert den Befehl "private int tomatoes <=0" dem Abschnitt "Fields" hinzugefügt. Damit die gefressenen Tomaten auch gezählt werden, mussten wir den Befehl "tomatoes <= tomatoes +1" unter dem Abschnitt "if (isTouching(Tomato.class))" der "act" Methode hinzufügen.

![Screenshot01](Bilder/Screenshot.Greepzaehlttomarten.png "Greep!")

#### Aufgabe acht:

Wir haben den Befehl unter der "act" Methode eingesetzt. Hierbei ist es egal, ob er sich direkt bei den anderen Befehlen, die mit den Tomaten zusammenhängen, befindet, oder nicht.

![Screenshot01](Bilder/Screenshot.Lernaktivitaeteinsende.png "Greep")

### Lernaktivität zwei

#### Aufgabe eins:

Öffnet man das "CheatSheet", so erscheint eine Liste von möglichen Kommandos, und entsprechenden Kurzbefehlen (-> Hotkeys).

#### Aufgabe zwei:

Benutzt man einen der Hotkeys, so erscheint das jeweilige Kommando, samt eines Eingabefeldes in der "act" Methode. Drückt man "escape", so verschwindet die Kommandospalte wieder. Gibt man einen Text in das Eingabefeld ein und drückt dann auf "escape", so passiert gar nichts.

Markiert man den gesamten eingegebenen Text und drückt "backspace", so verschwindet der eingegebene Text, dass Kommando bleibt und lässt sich nun wieder mit "escape" entfernen.

#### Aufgabe drei:

Wählt man die beiden Befehle "move" und "turn" aus, und wählt "disable", so bewegt sich die Katze gar nicht mehr, wenn man "act" drückt. Wählt man nun "enable", so dreht sie sich wieder im Kreis.

#### Aufgabe vier:

![Screenshot01](Bilder/screenshot_doppelter_dialog.jpg "fatcat")

Unter "inherited from actor" findet man alle Methoden, die die klasse "actor" ausführen kann, wie beispielsweise die Methode "move".

Unter "inherited from cat" findet man Methoden, die speziell für die Katze programmiert worden sind, wie beispielsweise "is hungry".


## Elfte Stunde <a name="8"></a> 

#### Aufgabe vier (Fortsetztung):

Unter dem Pfeilkopf in der Klassendefinition sind die gleichen Methoden aufgelistet, wie vorhin unter "inherited from actor", beziehungsweise "inherited from cat".

Unter der "birds eye view" im Stride-Quelltext findet man die Methoden, die auch unter "inherited from cat" zu finden sind.

#### Aufgabe fünf:

![Screenshot01](Bilder/Screenshot.fatcat1.png "Fatcat")

Wir haben einen neuen Methodenaufruf geöffnet. Drückt man nun "Steuerung" und "Space", so öffnet sich ein Menü mit allen Methoden, aus denen man auswählen kann.

Wählt man nun den Buchstaben "i", so reduziert sich die Auswahl der möglichen Methoden auf alle diejenigen, die mit einem "i" anfangen.


## Zwölfte und dreizehnte Stunde <a name="9"></a> (Doppelstunde)

### Lernaktivität drei

#### Aufgaben eins bis fünf:

Wir haben die Katze essen, schlafen und tanzen lassen, indem wir die entsprechenden Befehle (eat(), sleep(how long), dance()) in der act-Methode hinzugefügt haben.

Wir haben uns eine eigene Routine für die Katze überlegt. Diese besteht daraus, "Hooray!" zu rufen, sich schlafen zu legen, sich dabei einmal um sich selbst zu drehen, und anschließend noch einmal "Hooray!" zu rufen.
![Screenshot01](Bilder/Screenshot.Fatcateigeneroutine.png "FatCat")

#### Aufgaben sechs bis acht:

Wir sollten die Katze mit Hilfe eines if-Befehls tanzen lassen, wenn sie gelangweilt ist, und schlafen lassen, falls sie müde ist.
![Screenshot01](Bilder/Screenshot.fatcatifbefehle.png "FatCat")

Die Katze befolgt nun zusätzlich den Befehl, wenn sie hungrig ist, ein Stück Pizza zu essen.

#### Aufgaben neun bis zehn:

Die Aufgabe war es, die Katze schlafen zu lassen, falls sie müde ist. Anschließend sollte sie "Hooray!" rufen. Wenn sie nicht müde ist, sollte sie nur "Hooray!" rufen. Um die Katze müde zu machen, kann man sie tanzen lassen. Dies funktioniert mit einem Rechtsklick auf die Katze, dann kann man unter "inherited from actor" die Methode "dance" auswählen.
![Screenshot01](Bilder/Screenshot.fatcatsleepHooray.png "FatCat")

