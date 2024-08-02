
TARGET DECK
Softwaretechnik I

Interaktionsdiagramme
--
## Definition
***
Die Interaktionsdiagramme zeigen die für einen bestimmten Zweck notwendigen Interaktionen, dafür sind die Klassendiagramme die Grundlagen.
### Kollaborationsdiagramme
Diese erlauben es und kommunikationen zwischen Klassen einzuzeichnen
![[Pasted image 20240513115059.png]]
### Zeitdiagram
Zeigen so bisschen die Veränderung der Enums, Variablen unso
![[Pasted image 20240513115132.png]]
### Interaktionsübericht
![[Pasted image 20240513115318.png]]
## Sequenzdiagramme
***
>[!warning]
>Ein Sequenzdiagramm ermöglich die **exemplarische** Darstellung ***eines*** möglichen Ablaufs; es wird wird also ein spezieller Use-Case dargestellt

Wir beschränken uns hier in der Vorlesung auf diese.
Sequenzdiagramme sind **exemplarisch**. Sie wurden ursprünglich für die Modelierung von Telekommunikationsdienste entwickelt. Die Zeit läuft in Sequenzdiagramme von oben nach unten und es ist die frage immer "was muss wo passieren damit was wo passieren kann". Sequenzdiagramme haben den vorteil, dass sie intuitiv sind und um Integrationstestfälle, Protokolle (für verbotenes verhalten) und erlaubten nachrichtenverlauf zu beschreiben.
Man kann mit Sequenzdiagrammen sogar Synchrones verhalten so irgendwie darstellen ob etwas als sofortige Antwort passiert. (KEINE VOLLSTÄNDIGE VERHALTENSBESCHREIBUNG! NUR EXEMPLARISCH)
### Beispiel
![[Pasted image 20240513121631.png]]
### Grundlegende Elemente
![[Pasted image 20240513120036.png]]
![[Pasted image 20240513120250.png]]
### Nachrichten
![[Pasted image 20240513120443.png]]
![[Pasted image 20240513120757.png]]
Was ich senden/empfangen kann sehe ich anhand der Sichtbarkeit der Methoden der Senderklasse
### Objekterzeugung und Löschung
![[Pasted image 20240513121158.png]]
### Koole Kontrollfluss Kalküle
![[Pasted image 20240513121550.png]]
Bsp, alt als verzweigung, loop als schleife. Beides Sparsam verwenden!
![[Pasted image 20240606163248.png]]

## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt