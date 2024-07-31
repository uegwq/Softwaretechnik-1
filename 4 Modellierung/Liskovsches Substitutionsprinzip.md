
TARGET DECK
Softwaretechnik I

Liskovsches Substitutionsprinzip
--
## Definition
***
Das Prinzip besagt folgendes: Wenn U eine Unterklasse von O ist, muss ich alle Auftretungen von O durch U ersetzten können müssen, und das Programm muss noch funktionieren müssen.
## Folgerungen
***
- Alle Eigenschaften der Oberklasse stehen der Unterklasse zur verfügung.
- Die Unterklasse kann noch zusätzliche Eigenschaften definieren um die Oberklasse spezieller zu machen
- Die Unterklasse darf aber keine Eigenschaften Weglassen.
	  - Dann ist es nicht mehr so einfach eine Unterklasse. Das Liskovsche Substitutionsprinzip wäre verletzt.
+ Die Unterklasse hat die gleichen oder schwächere Vorbedingungen als die Oberklasse.
+ Die Unterklasse bietet die gleichen oder stärkeren Nachbedingungen wie die Oberklasse.
+ ! Unterklassenmethoden dürfen nicht mehr erwarten und weniger liefern.
## Parameter-Varianz
***
- Varianz - Modifikation der Typen der Parameter einer überschriebenen Methode
- Kovarianz - Verwendung einer Spezialisierung des Parametertyps in der überscheibenen Methode
- Kontravarianz - Verwendung einer Verallgemeinrung des Parametertyps in der überschreibenden Methode
- Invarianz - keine Modifikation des Typs
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt