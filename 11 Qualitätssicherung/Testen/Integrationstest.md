
TARGET DECK
Softwaretechnik I

Integrationstest
--
## Definition
***
Damit ist gemeint, dass wir die einzelnen Komponenten schrittweise zum Gesamtsystem testen und zum Gesamtsystem zusammenfügen.

Unmittelbar ist schlecht, denn dafür muss erst das ganze System fertig sein :(![[Pasted image 20240718155936.png]]
Vorgehensorientiert: Integrationsreihenfolge je nach Systemarchitektur, genauer plan was getan werden soll

Testzielorientiert: Testfälle schreiben anhand der Testziele, Ziel ist möglich

Big bang: Wir nehmen alle unsere Module und testen sie alle auf einmal und hoffen, dass es funktioniert
Top-down: Hier fangen wir in der höchsten hierarischen schicht (meistens user-interface) an und gehen nach unten durch und testen ob alles klapp
Bottop-up: Wir fangen ganz unten in der hierachischen schicht an und gehen nach oben
Hardest-first: Wir testen die kritischte schicht als erstes, die erste die wir testen ist dann die kritischte
Outside-in: top-down und bottom-up gleichzeitig, wir gehen aber von der obersten schicke und von der unteren schicht durch. (sehr gut scheinbar!)
Inside-out: so invers
Nach verfügbarkeit: Wir testen halt die Sachen, die wir schon geschrieben haben
Funktionsorientiert: Wir testen anhand den funktionalen testfällen und orientieren und an den funktionalen Anforderungen
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt