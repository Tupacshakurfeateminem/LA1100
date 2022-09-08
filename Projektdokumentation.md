☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

✍️ Ihr Gruppenname und Ihre Nachnamen

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Ich muss ein Programm programmieren das es ermöglicht eine Zahl zwischen 1 und 100 zu erraten und mir Tips gibt ob ich zu hoch oder zu Tief gereten habe.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |      muss       |  F   | Als ein Casinobetreiber möchte ich das der Computer eine geheim Zahl zwischen  1-100 speichert damit ich eine Jackpotzahl habe |
| 2    |      muss       |  F   |    Als ein Casinobetreiber möchte ich das der Benutzer Zahlen eraten kann,damit Er auch gewinn oder verlust machen kann|             | 3    |      muss       |  F   |    Als ein Casinobetreiber möchte ich das der Computer  nach jeder geratener Zahl einen Hinweis gibt, damit er mehr einsetzt  a.	Die                                 |geratene Zahl ist niedriger als die Geheimzahl. b.	Die geratene Zahl ist grösser als die Geheimzahl. c.	Die Geheimzahl wurde erraten
| 4    |      muss       |  F   |  als ein Casinobetreiber möchte ich das sobald die GeheiZahl erraten wurde Sollten die Versuche die die Person benötigt hat angezeigt                                                 werden, damit ich denn Jackpot minimieren kann.|
| 5    |      muss       |  Q  |Als ein Casinobetreiber möchte ich das das Programm mit Fehleingaben    umgehen oder sie vermeiden kann, damit ES keine Störungen gibt| 

                                           
✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |Testen ob es eime geheime Zahl zwischen 1 - 100 gibt| 10 |  richtige antwort |  
|  1,2 | Zahl raten |  8  | das ist nicht die korrekte Zahl |
| 1,3 |  Für die geratene Zahl Feedbacka)die geheim Zahl ist niedrigerb)die geheime Zahl ist grösserc) die geheime Zahl ist richtig|                      7     |   die geheim Zahl ist grösser|
| 1,4 sobald erraten Anzahl versuche anzeigen        |               10      |       richtig Versuche : 3|     
|1,5 | sobald eine Fehleingabe eingegeben  wird damit umgehen |                         zehn     |          0 |
|1,6 |sobald der Spieler geraten hat fragen ob er weiter spielen will |   y    |    geben Sie eine Zahl zwischen 1 -100 ein|

          
          
          
          
          
✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme


✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |         tatsächliche Zeit 
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |1.9.2022    ich   | ich informiere mich im Internet | 45 |30  |
| 1.b | 1.9.2022|   ich   | Ich Programmiere eine Zahl zwischen 1-100|45 |                      
| 2   | 1.9.2022 |  ich      Programmiere ob die Zahl richtig oder Falsch ist |45  |30|                        
|2b   | 1.9.2022 |    ich |    Programmiere das richtig oder falsch angezeigt wird |30  |20 |
| 3   | 1.9.2022 |     ich |    weiterspielen y/ no    |     60      |      45      |  
 |4   | 1.9.2022 |   ich   |   ist die Zahl grösser oder kleiner    |   60       |       25 |     
|5  | 1.9.2022   | ich    |Fehlermeldung wenn keine Ziffer eingegen ist erstellen |    45  |                20|
| 6 | 8.9.2022  | ich     | weiterspielen yes or no programmiere bei yes Forgang wiederholen bei no spiel beenden | 45|?| 

 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A) |  1.9.2022 | ich  |        45     |          30|
| 1.b) |  1.9.2022 |  ich  |        45    |           45|
| 2.a) |  1.9.2022 | ich   |       45 |              30 |
| 2.b)  | 1.9.2022 | ich     |     30   |            20| 
| 3)   |  1.9.2022 | ich    |      60     |          45|
| 4)   |  1.9.2022 | ich   |       60    |           25 |
|  5)  |   1.9.2022 | ich    |      45  |             20|
 | 6)  |   8.9.2022 | ich    |      45|100|


✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
