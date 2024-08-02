
TARGET DECK
Softwaretechnik I

Klassendiagramme
--
## Mini Steckbrief
***
![test](<Pasted image 20240503103546.png>)
## Definition
***
Es geht hierbei um Modelierung von Daten.
Merke: Eine Klasse ist eine Sammlung von Objekten mit gemeinsamen Eigenschaften, Einschränkungen und Semantik.
## Objekt
***
Ein Objekt ist von einem anderen Objekt eindeutig unterscheidbar, also ein bestimmbares Element.
$\Omega$ ist die Menge aller Objekte
### Attribut
Ein Attribut ist eine Eigenschaft die für alle Objekte eines Typs gelten. Z.b. Apfel: Farbe (rot/grün), Angebissen (Ja,nein)
### Objektidentität
Die Existenz eines Objektes ist unabhängig von einen Attributwerten, sie sind also auch unterscheidbar, wenn ihre Attribute gleich sind. Also alle Äpfel die Rot und Angebissen sind, sind nicht gleich.
### Zustand eines Objekte
Wenn zwei Objekte dieselben Zustände haben reagieren sie auf ihre Umwelt gleich (hmmm)
### Kapselungsprinzip
Der Zustand ist zwar nach außen sichtbar, er wird aber im Inneren des Objektes verwaltet.
	Beispiel: Wenn sich der Wert des Attributes „Restzeit“ eines Objektes „Eieruhr“ auf 0 ändert, wechselt die „Eieruhr“ in den Zustand „Klingeln“.
### Methoden
Methoden können den Zustand eines Objektes verändern.
Problem: Wann das ich welche Botschaft an ein Objekt senden
- Antwort: Das spezifiziert man mit einem Zustandsübergangsdiagramm (siehe später)
#### Methodensignaturen
Eine Methodensignatur besteht aus:
- Methodenname
- Rückgabetyp
- Parameterliste
## Klasse
***
![[Pasted image 20240429121656.png]]
## Attribute
***
#### Attribute Generell
![[Pasted image 20240429121821.png]]
#### Attribut mit Datentyp (Als Referenz auf ein anderes Objekt)
![[Pasted image 20240429121950.png]]
## Operation
***
![[Pasted image 20240429122047.png]]
#### Parameter für Operationen
![[Pasted image 20240429122147.png]]
#### (Statische) Klassenatribute
Sie werden unterstrichen und dann sind sie statisch.
###### Beispiel:
![[Pasted image 20240802124822.png]]
## Assoziation
***
Wenn zwei Klassen sich kennen sollen (z.b. Person und Firma), dann haben sie eine Assoziation
![[Pasted image 20240429123014.png]]
![[Pasted image 20240429123028.png]]

Es gibt drei Typen von Assoziationen: 
### Aggregation
Die Aggregation ist ein Spezialfall der Assoziation mit dem Namen „besteht aus“ und besteht zwischen dem Aggregat und seinen Teilen. Meist haben Aggregat und seine Teile eine gemeinsame Lebensdauer.
![[Pasted image 20240503100257.png]]
### Komposition
Ein Spezialfall der Aggregation ist die Komposition. Eine Komposition besteht zwischen einem Kompositum und seinen Komponenten.
Kompositum hat alleinige Verantwortung für Erzeugung/Löschung seiner Komponenten. Kompositum gelöscht à alle seine Komponenten gelöscht.
![[Pasted image 20240503100334.png]]
### Vererbung

>[!Quote] Liskovsches Substitutionsprinzip
>In einem Programm, in dem $U$ eine Unterklasse von $O$ ist, kann jedes Exemplar der Klasse $O$ durch ein Exemplar von $U$ ersetzt werden, wobei das Programm weiterhin korrekt funktioniert. 
>$\implies$ Jedes benutzte Säugetier Objekt kann durch ein Katzen Objekt ersetzt werden.

>[!quote] Aus der VL
>"Vererbung braucht man eigentlich nur ganz selten und in den Klausuraufgaben schreien Formulierungen immer nach Vererbung."

Eine Vererbungsbeziehung von einer Klasse K1 zu einer Klasse K2 ist eine Beschreibung der Tatsache, dass alle Objekte der Klasse K2 zusätzlich zu den in der Klasse K2 beschriebenen Eigenschaften auch alle Eigenschaften der Klasse K1 haben.
![[Pasted image 20240503103621.png]]
## Schnittstellen
***
Eine Schnittstelle ist eine Art Klasse mit Methoden, ohne eine Konkrete Implementierung. Klassen, die eine Schnittstelle implementieren füllen diese Methoden mit Leben :O. Man kann dann diese Schnittstellenunterklasse verwenden wie das Liskovsche Substitutionsprinzip. 
![[Pasted image 20240802130132.png]]
## Sichtbarkeit
***
Die beiden wichtigen Sichtbarkeitsstufen lauten:
- ("-") - privat
- ("+") - öffentlich
![[Pasted image 20240802151527.png]]
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt