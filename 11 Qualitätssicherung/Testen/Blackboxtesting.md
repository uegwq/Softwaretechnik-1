
TARGET DECK
Softwaretechnik I

Blackboxtesting
--
## Definition
***
Man hat keinen Code, sondern nur eine Beschriebung davon, wie sich das Programm verhält. Wir leiten 
## Übungsblatt 5 Copy paste (delete me)
***
$$D_{\text{valid week}}= [1,52]$$$$D_{\text{invalid week}}= \Bbb Z \setminus [1,52]$$$$W_{\text{valid day}}= [1,7]$$$$W_{\text{invalid day}}= \Bbb Z [1,7]$$
Testfall 1 (Day wertebereich):
$D_\text{valid week},D_{\text{invalid week}}$

| day | week | output |
| --- | ---- | ------ |
| 1   | -5   | FEHLER |
| 1   | 4    | Liste  |
| 1   | 90   | FEHLER |
Testfall 2 (Week wertebereich)
$W_{\text{valid day}},W_{\text{invalid day}}$

| day | week | output |
| --- | ---- | ------ |
| -4  | 13   | FEHLER |
| 4   | 13   | Liste  |
| 10  | 13   | FEHLER |
Testfall 3 (Grenzwerte)
$D_\text{valid week},D_{\text{invalid week}}, W_{\text{valid day}},W_{\text{invalid day}}$

| day       | week      | output |
| --------- | --------- | ------ |
| -1        | 1         | FEHLER |
| 0         | 1         | FEHLER |
| 8         | 1         | FEHLER |
| INTLIMIT  | 1         | FEHLER |
| -INTLIMIT | 1         | FEHLER |
| 1         | -1        | FEHLER |
| 1         | 0         | FEHLER |
| 1         | 53        | FEHLER |
| 1         | INTLIMIT  | FEHLER |
| 1         | -INTLIMIT | FEHLER |
Testfall 4 (Normale Interaktion)
$D_\text{valid week},D_{\text{invalid week}}, W_{\text{valid day}},W_{\text{invalid day}}$

| day | week | output |
| --- | ---- | ------ |
| 1   | 1    | Liste  |
| 7   | 1    | Liste  |
| 1   | 51   | Liste  |
| 1   | 52   | Liste  |
Diese Testfällt sind sinnvoll, da sie
1. Generell schauen, ob einfache Überschritte des Grenzrahmens abgefangen werden
2. Fehlverhalten an den Grenzwerten getestet wird
3. Fehlverhalten an den Extremwerten (INTLIMIT) getestet wird
4. Eine ganz Normale Interaktion überprüft wird
Dies sind Fälle, die sehr oft auftreten und hier sehr günstig überprüft werden können.

## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt