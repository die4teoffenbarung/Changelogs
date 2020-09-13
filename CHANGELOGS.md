# [Changelogs](https://www.d4o.info/index.php/das-spiel/server/changelogs/326-version-dev.html)
Alle Änderungen für den Live-Server werden [hier](https://www.d4o.info/index.php/das-spiel/server/changelogs/326-version-dev.html) eingetragen.

Das Changelog-Styling basiert auf [Keep a Changelog](https://keepachangelog.com/de/1.0.0/).
## [0.9-UNRELEASED] [Client / Server v1.79 Rev002] 13-09-2020
### Client / Server
- Offizielle Dialsoft Änderungen und Neuerungen aus v1.74-DS migriert. 
Wir sind hier noch nicht komplett fertig und einige unserer Features müssen noch eingebaut werden.
- DirectX fix
- Verbesserte Client-Stabilität
- Schnellere Ladegeschwindigkeit
- Reibungsloseres Gameplay
- "Vollbild" -Modus hinzugefügt (Alt + Enter)
- Der Befehl "Xpstat" gibt Ihnen Ihre XP und / oder Statistiken
- Option hinzugefügt: Verstecke Nachricht über Gold-Drop wenn Monster sterben
- Hinzufügen eines Tastaturziels
Um ein Tastaturmonster als Ziel zu wählen, musst du es mit Tab auswählen und durch Klicken auf seine Lebensleiste validieren.
TAB wählt das nächste Monster aus, mit "Shift" kehrt man zum vorherigen Monster zurück
- Debug-Ignorierliste
- Änderung der Verknüpfung zur Anzeige der Karte Strg + Tab
- Verbesserte Lesbarkeit von Beträgen
- Hinzufügen eines Tausendertrennzeichens (Beispiel: 1000000 wird 1.000.000)
- Rechtsbündige Ausrichtung im Auktionshaus
- Farben im Questbuch hinzugefügt (Aktuell nicht in verwendung)

### NPCs

### Items

### Skill

## [0.8u] [Client / Server v1.78 Rev018] 12-05-2020
### Client / Server
- Einen Bug gefixt, durch den der XP-Multiplikator in Gruppen doppelt angewendet wurde.
- Einen Bug gefixt, durch den Charaktere in Gruppen inselübergreifend gelevelt werden konnten.
- Die Verzögerung der Trefferpunkte anzeige von Gruppenmitgliedern wurde minimiert.
### NPCs
- Marawings Flügel-Wiederherstellung wurde behoben.
- Tür zur Göttlichen Truhe prüft ab jetzt die Entfernung, wenn man mit ihr spricht.
### Items
- Gürtel des Instabilen schutzes kostet jetzt, wie eigentlich schon immer vorgesehen, Mana in höhe des aktuellen Levels.
- Große Zuckerstange des Weihnachtsmanns erhöht das Glück so lange sie angelegt ist.
### Skill
- Rundumschlag hatte einen Fehler, welcher behoben wurde, der unter ganz gewissen Umständen dazu führte, dass er nicht mehr Ausgeführt werden konnte bis ein Staff diesen zurücksetzte.

## [0.8t] [Client / Server v1.78 Rev018] 27-11-2019
### NPCs
- Weihnachtsmann verschenkt erst wenn ein gewisser Obolus entrichtet wurde. 
### Monster
- Alle Wespen-Kills sollten jetzt in der Ranglisten zählen.
## [0.8s] [Client / Server v1.78 Rev018] 13-11-2019
### Client / Server
- Windows 7/8/10-Boost hat ein Update erhalten und sollte unter Anderem Fehler mit gewisser Hardware beseitigen.
### Monster
- Krieger des Einäugigen haben eine weitere Schadensanpassung erhalten.
- Höllenhund hat einige Korrekturen erhalten. Unter anderem sollte jetzt jeder Kill gezählt werden und die Welpen erscheinen am Charakter.
### Items
- Grimoire der Unterwelt hatte einen Fehler durch den die Boosts nicht mehr richtig berechnet werden konnten.
- Adamant beschlagener Mondstein kann nicht mehr abgelegt werden.
### Event
- Geisterwochen etwas verlängert, allerdings nur noch einige Tage aktiv.

## [0.8r] [Client / Server v1.78 Rev017] 13-10-2019
### Client / Server
- Automatisches Sanktionen-System aktiviert. Es stellt sicher dass unsere Server-Regeln eingehalten werden.
### NPCs
- Wiederholen/Kaufen einer Wiedergeburt bei Erzmagier Grim setzt das Karma nicht mehr zurück.
- Rauru sollte jetzt alle Gegenstände beim Binden abnehmen.
- Aloysius Sternenstrahl tauscht ab jetzt alle mitgeführten Spinnenaugen statt immer nur ein Paar.
### Monster
- Mondstein-Drops beim Einäugigen haben jetzt alle die gleiche Drop-Chance und sollten sehr selten fallen gelassen werden.
- Krieger des Einäugigen haben eine weitere Schadensanpassung erhalten und weichen etwas mehr aus.
### Items
- Mithril Katar +2 wird wieder angezeigt, wenn es angelegt wurde.
### Event
- Geisterwochen wurden aktiviert.
- Neuer Titel erspielbar: `Geisterjäger/in`
### Sonstiges
- Blocking-Fehler korrigiert.

## [0.8q] [Client / Server v1.78 Rev017] 28-09-2019
### Client / Server
- Befehle `!Names` und `strg+n` zeigen keine Monster-Namen mehr an.
### NPCs
- Mara Wing gibt jetzt die korrekten Flügel für `Leuchtende hellblaue Flügel` und `Leuchtende grünrote Flügel` raus.
### Monster
- Krieger des Einäugigen haben zu Testzwecken erst einmal eine kleinere Schadensanpassung erhalten und sollten nicht mehr ganz so häufig Treffen.
###Zauber
- Seuche wurde etwas angepasst, um Fehler bei gewissen Monstern vorzubeugen.
### Items
- Buch des Propheten wurde korrigiert, es gibt ab jetzt `+20 Lichtmagie [Vorher 15]` und `+15 Dunkel-Resistenz [Vorher -15]`
- Armband der Flammen wurden die gemeldeten Fehler beseitigt. Außerdem hat es nach der Nutzung wieder eine Wartezeit. Die Wartezeit beträgt nur noch 3 Sekunden.
### Homepage
- Waffen im Lexikon haben seit kurzem wieder Schadenswerte, diese sollten jetzt weitestgehend korrekt sein.

## [0.8p] [Client / Server v1.78 Rev016] 20-09-2019
### Client / Server
- Meditieren zeigt ab jetzt eine `Meditiert` benachrichtigung und das regenerierte Mana an.
- Ein Fehler wurde behoben, bei dem die `Betäubt!` Benachrichtigung bei gewissen Umständen nicht korrekt dargestellt wurde.
### Monster
- Krieger des Einäugigen und Zeithüter hatten durch einen Hotfix, der eigentlich keine Echte Änderung darstellen sollte, eine nicht korrekte Berechnung von Schaden/Reichweite zur Folge.
### NPCs
- Barius aggiert ab jetzt korrekt wenn man das Schlüsselwort `Trank herstellen` anklickt.
### Items
- Armband der Flammen löst nur noch aus wenn der Charakter sich auch aktiv am Kampf beteiligt.
### Sonstiges
- Lagerkiste und Familien-Lager wurden getrennt. 
- Diverse Textkorrekturen.

## [0.8o] [Client / Server v1.78 Rev016] 11-09-2019
### Client / Server
- WICHTIG: T4CConfig.exe hat eine neue Funktion zum ein- und ausschalten der Grafikengine-Optimierung: `Boost Windows Vista, 7, 8, 10`. 
Jeder sollte individuell, durch ausprobieren, die beste Einstellung für das eigene System herausfinden.
- Webpatch wurde optimiert und wird vor dem Start des Clients geprüft.
- Fehler mit zwei oder mehr Bildschirmen wurde behoben. Das Spiel sollte beim versuch das Fenster auf einen sekundären Monitor zu verschieben nicht mehr crashen.
- Haustiere konnten durch einen Fehler nicht mehr herbeigerufen werden, diesen haben wir behoben.
- Solltet ihr einen Gegner betäuben werdet ihr über die Schadens-Nachricht darüber informiert.

### Items
- Jarkos Zauberbuchs Schaden wurde drastisch reduziert.

## [0.8n] [Client / Server v1.78 Rev011] 23-08-2019
### Client / Server
- Kleinere Anpassung für eine bessere/korrekte Darstellung der Benutzeroberfläche.
- T4CConfig.ini wurde in D4OConfig.ini umbenannt und sollte automatisch vom Client erkannt/kopiert werden.

## [0.8m] [Client / Server v1.78 Rev009] 21-08-2019
### Client / Server
- Anpassungen für verbesserte Kompatibilität mit aktuellen Windows-Betriebssystemen. Wir hoffen es läuft bei allen weiterhin ohne größere Probleme.
- Die Schrift im Fenstermodus sollte ab jetzt nicht mehr pixelig wirken wenn das Fenster vergrößert wird.
- Problem mit fehlenden Rechtsklick-Hilfetexten im GUI wurde behoben.
### Monster
- Der Einäugige hat ein paar kleinere Anpassungen erhalten außerdem verflucht er Helden nicht mehr.

## [0.8l] [Client / Server v1.78 Rev005] 16-08-2019
### Client / Server
- Rechtsklick auf Auktionshaus-Items sollte nicht mehr zum Absturz des Clients führen.
### Homepage
- Spielzeit Ranking wurde aktiviert und unter `Community->Ranking->Spielzeit` zu finden.
## [0.8k] [Client / Server v1.78 Rev005] 11-08-2019
### Client / Server
- Client-Start beschleunigt
- Doppel-Rechtsklick auf einen Gegenstand ohne "Item-Info" öffnet ein neues Browser-Fenster zu unserem Lexikon und sucht automatisch nach diesem Gegenstand.
- Item-Infos haben jetzt einen "Suchen-Button", dieser öffnet ein neues Browser-Fenster zu unserem Lexikon und sucht automatisch nach diesem Gegenstand.
- Der Angriffsmodus hat ein neues Icon erhalten.
- Fehlende Grafiken wurden hinzugefügt.
- Gilden-/Familien-Protokolle (Logs) werden wieder angezeigt.
- Neben "GM-Rufen", im Chat-Center, haben wir einen Button direkt zu unserem Ticket-System gesetzt.
- Schreibe im Öffentlichen-Chat eine Nachricht welche `@team` beinhaltet, das Team wird dann über diese Nachricht informiert. (Test-Funktion, kann jederzeit entfernt werden.)

### Items
- Ketzermantel der Arkanen Magie benötigt ab jetzt jeweils 285 Intelligenz und Wissen.
- Kelch Met wird jetzt in die Korrekte Kategorie der Strukturierten-Lager einsortiert.
- Seraphen-Rüstungsteile benötigen ab jetzt 115 Ausdauer, die Rüstung ist Golden-Farben und wurde etwas aufgewertet.

### NPCs
- Mara Wing reagiert nun korrekt auf das Schlüsselwort für die Farbenfrohen und leuchtend roten Flügel.
- Königlicher Schreiber hatte einen Fehler in der Karma-Berechnung und wurde behoben. Die zu unrecht verteilten Titel wurden entfernt. 
- Linhartd Nebelschneider konnte den Umhüllten-Mondstein nur unter ganz bestimmten Umständen herstellen, er sollte jetzt immer korrekt reagieren.

### Zauber
- Läuterung macht ab jetzt mehr Schaden.

### Monster

### Event

### Sonstiges
- Blocking korrektur bei Jarkos Tor.
- Diverse Text-Korrekturen.

## [0.8j] [Client / Server v1.77 Rev012] 16-06-2019
### Client / Server
- Willkommensnachrichten beim betreten der Welt wurden erweitert. (Werden nach und nach aktiviert.)

### Items
- Zuckerstange des Weihnachtsmanns funktioniert jetzt wie beabsichtigt.
- Jarkos Truhe hatte ein Blocking-Problem und wurde behoben.
- Hasenohren und die Hasenpfote von Kung wurden auf einen Zauber reduziert und die Zauber-Beschreibung angepasst.
- Grimoire der Unterwelt's Zauber sollte nicht mehr auslaufen.
- Glückstrank Zauber-Beschreibung angepasst.

### NPCs
- Spenden-NPCs haben ein paar Textkorrekturen erhalten.
- Bischof Krähbanner's Magenverstimmung dauert nur noch halb so lange an wie üblich.

### Monster
- Krieger des Einäugigen führen ihren Solarplexushieb nicht mehr so häufig aus, im gleichen Zug haben wir die Reichweite der Fähigkeit großzügig reduziert.

### Event
- Oster-Event ist beendet.

### Homepage
- Familien-Liste funktioniert wieder wie gewohnt
