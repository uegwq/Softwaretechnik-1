
TARGET DECK
Softwaretechnik I

Anwendungsfalldiagramm (use case diagram)
--
## Definition
***
Was will der Nutzer von seinem System? Wer sind die Akteuere?

Wichtig: Anwendungsfalldiagramme sind ein Hilfsmittel zur Anforderungsermittlung und -verwaltung. Sie zeigen nur Zusammenhänge der an Anwendungsfällen beteiligten Modellelemente. Anwendungsfalldiagramme modellieren kein Verhalten und keine Abläufe!

![[Pasted image 20240429115805.png]]
## Elemente
***
![[Pasted image 20240802121632.png]]
![[Pasted image 20240802121237.png]]
## Beziehungen zwischen den Elemente
***
1. Assoziation / Kommunikation von Akteur und einem Anwendungsfall
		![[Pasted image 20240802121721.png]]
2. Multiplizität von Akteur und Anwendungsfall
		![[Pasted image 20240802121744.png]]
		Zwei oder mehr Player sind in den Use-Case "PlayGame" involviert. Jeder Player nimmt an genau einem "PlayGame" teil.
3. Generalisierungen
		![[Pasted image 20240802121909.png]]
		![[Pasted image 20240802121916.png]]
4. Include-Beziehung
		![[Pasted image 20240802121953.png]]
5. Extends beziehung
		Die Extends-Beziehung wird verwendet, wenn ein Use-Case vollständig ist, aber ein anderer Use-Case die Funktionalität erweitert.
		![[Pasted image 20240802122107.png]]
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt