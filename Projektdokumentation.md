# Projekt-Dokumentation

Özden, Heiniger
Mirhan Özden
| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

In unserem Projekt programmieren wir in Unity ein 2D Spiel, welches verschiedene Levels hat.

✍️ Erklären Sie genauer in 50 bis 100 Wörtern, was genau Sie in diesem Projekt erreichen möchten, und was Sie dabei zu lernen hoffen.

Wir möchten lernen, wie man verschiedene Levels erstellt und wie man auf diese zugreiffen kann, beziehungsweise spielen kann.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  muss               | funktional     | Als ein Spieler möchte ich mich 2D bewegen können, damit ich ins Ziel komme. |
| 2  |  muss               | funktional     | Als Spieler möchte ich, dass mich die Kamera verfolgt, damit ich sehe was ich mache.|
|3|kann|Qualität|Als Spieler möchte ich Münzen im Spiel haben, die ich einsammeln kann, damit ich im Spiel auf etwas anderes achten muss als Gegner.|
|4|muss|Funktional|Als Spieler möchte ich Gegner haben, damit das Spiel eine gewisse Schwierigkeit bietet, damit das Spiel nicht langweilig und kurz wird.|
|5|muss|Funktional|Als Spieler möchte ich ein Lebenssystem haben, welches mein aktuellen Healthstand anzeigt, damit das Spiel eine Schwierigkeit bietet|
|6|kann|Rand|Als Spieler möchte ich zusätzlich zu den Gegnern Hindernisse haben, damit ich zusätzlich noch auf die Umgebung aufpassen muss und das Spiel interessanter wird.|
|7|kann|Qualität|Als Spieler möchte ich Animationen haben, damit das Spiel flüssig aussieht und ich nicht gestört werde, |
|8|kann|Qualität|Als Spieler möchte ich mit den Münzen etwas kaufen können, damit das Spiel nicht langweilig wird und dass das Geld einen Nutzen hat. |
|9|muss|Funktional|Als Spieler möchte ich verschiedene Levels spielen können, damit das Spiel nicht immer gleich ist.|
|10|muss|Funktional|Als Spieler möchte ich Waffen verwenden (mind. 2), damit ich die Gegner besiegen kann.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| 2.2  |              |         |                   |
|||||
|||||
|||||
|||||
|||||
|||||

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

✍️Fügen Sie hier ein Use Case-Diagramm mit mindestens 3 Anwendungsfällen ein; und eine Skizze davon, wie Ihre Netzseite aussehen sollte.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |18.10       | Mirhan          | Skript für den Player, damit man ihn bewegen kann.             | 60             |
| 2.A  |18.10       | Lukas          | Skript, damit die Kamera nicht statisch ist sondern sich mit dem Spieler mit bewegt             | 20min              |
| 3.A  |18.10      |Lukas           |Skript um Münzen einzusammeln.              | 45min              |
| 7.A  |18.10      | Lukas          |  Animationen hinzufügen            | 45min              |
| 4.A  |18.10       |  Mirhan         | Gegner für das Spiel erstellen             | 60min              |
| 5.A  |25.10      |Lukas           | Funktion, damit der Spieler Schaden erleiden kann wie auch sterben.             | 45min              |
| 6.A  |25.10       | Mirhan          |   Hindernisse hinzufügen           | 45min              |
| 10.A  |25.10       |  Lukas         | Waffe 1 erstellen             | 45min              |
| 10.B  | 25.10      | Lukas          | Waffe 2 erstellen             | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |
| 1.A  |       |           |              | 45min              |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.

