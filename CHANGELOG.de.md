# Änderungsprotokoll

Alle wichtigen Änderungen an Easylife. Die englische Fassung steht in `CHANGELOG.md`;
beide werden im Spiel unter "Neuigkeiten" angezeigt. Neue Einträge kommen unter "Unreleased".

## Unreleased

## 1.13.2 - 2026-10-26

### Sonstiges
- Easylife erscheint jetzt unter **github.com/dmm1/easylife-addon**: Download, Funktionsübersicht und Änderungsprotokoll. Lizenz: MIT.

## 1.13.1 - 2026-10-20

### Einfacher zu bedienen
- **Alt+Rechtsklick auf einen Gegenstand** in Taschen, Bank oder Baganator öffnet das Easylife-Menü (sperren, zum Verkauf markieren, immer verkaufen - für diesen Charakter, dieses Konto oder alle Konten -, verfolgen, Notiz). Ein normaler Rechtsklick benutzt den Gegenstand weiterhin. Der Tooltip nennt den Klick; beides lässt sich auf der Einstellungs-Hauptseite abschalten.

## 1.13.0 - 2026-10-20

### Einfacher zu bedienen
- **Taste für das Gegenstandsmenü:** eine Taste für alles - mit der Maus auf einen Gegenstand zeigen und drücken: Ein Menü bietet Sperren, Zum Verkauf markieren, Fürs Farmen verfolgen und Notiz an, je nachdem, was deine aktiven Module damit tun können. Festlegen im neuen Tab "Übersicht" (oder in den Tastenbelegungen des Spiels); die einzelnen Tasten bleiben.
- **Tab "Übersicht":** der erste Tab des Easylife-Fensters listet alle Tasten mit "Taste festlegen" direkt daneben, den Status der Konten-Synchronisierung, Minikarten-Symbol und Chat-Meldungen sowie jedes Modul mit seinen Einstellungen (oder "Einschalten").
- **`/el` öffnet das Easylife-Fenster** (wie das Minikarten-Symbol); `/el config` öffnet die Einstellungen.
- **Größe änderbar:** am Griff unten rechts ziehen; die Größe bleibt erhalten. Standardmäßig ist das Fenster etwas breiter.
- **Rechtsklick-Menüs in den Tabs:** Zeilen in "Gegenstandssperre", "Händler", "Farmen" und "Notizen" bieten ihre Aktionen auch per Rechtsklick (Optionen, Bereich, Bearbeiten, Karte, Löschen ...). Entfernen-, Löschen- und Karten-Knöpfe sind jetzt kleine Symbole, so bleibt mehr Platz für Namen.
- **Rückgängig:** Löschen einer Farm-Sitzung, einer Notiz oder eines Pins, einer "Immer verkaufen"- oder Sperrregel sowie das Löschen von Sammelpunkten zeigt 10 Sekunden lang eine Leiste "Rückgängig".
- **Chat-Meldungen:** neue Einstellung "Nur wichtige" (Hauptseite oder Übersicht) lässt Bestätigungen wie "gesperrt" oder "verfolgt" weg; Warnungen und Ergebnisse erscheinen immer. Der Gegenstand leuchtet kurz auf, wenn eine Taste gewirkt hat.
- **Direkt neu laden:** Ein- oder Ausschalten eines Moduls oder der Konten-Synchronisierung bietet "Jetzt neu laden" an statt einer Chat-Zeile.
- **Einstellungen:** Optionen, die nur mit einer anderen zusammen etwas bewirken (z. B. "Stufen unter deinem Charakter" unter "Niedrigstufiges Essen und Trinken verkaufen"), sind eingerückt und ausgegraut, solange diese aus ist. Die Hinweistexte sind kürzer; Details stehen in den Tooltips. Schließt du die über das Zahnrad geöffneten Einstellungen, kommt das Easylife-Fenster zurück.
- **Tastenbelegung:** Eine schon belegte Taste muss ein zweites Mal gedrückt werden, bevor sie ersetzt wird.
- Tabs und Module heißen gleich: Tabs "Gegenstandssperre" und "Händler", Modul "Notizen".

### Farmen
- Zum Farmen markierte Gegenstände heißen jetzt überall **verfolgte** Gegenstände (Taste, Tab, Farm-Anzeige, Item-Sets), damit sie nicht mit zum Verkauf markierten verwechselt werden.
- **Farm-Anzeige:** ein Zahnrad im Titel öffnet Item-Sets, Sitzungsziele und die Chat-Zusammenfassung (weiterhin auch per Rechtsklick); der Minus-Knopf verkleinert sie auf eine Zeile mit dem Gold pro Stunde. "Neu starten" fragt nach, sobald eine Sitzung etwas zu verlieren hat. Längere Gegenstandsnamen passen hinein.

### Behoben
- Der Hinweis zum Minikarten-Symbol in den Einstellungen nannte die falschen Tabs.
- Der Tab "Notizen" schnitt seine Zusammenfassung auf Deutsch ab; leere Gruppen fallen jetzt weg (Darüberfahren zeigt sie vollständig).

## 1.12.1 - 2026-10-20

### Farmen
- **Mit deinen anderen Konten geteilt:** bei eingeschalteter Konten-Synchronisierung gehen dein Verlauf (und damit die besten Orte), deine Sammelpunkte und Item-Sets auch an deine anderen WoW-Konten - nur lesbar und mit dem Konto gekennzeichnet: Verlaufszeilen ohne "Löschen", ihre Sitzungen zählen bei den besten Orten, ihre Sammelpunkte stehen auf der Karte, ihre Item-Sets lassen sich im Item-Set-Menü laden. Sammelpunkte werden gesendet, wenn eine Sitzung endet. Einstellung: "Farmdaten mit meinen anderen Konten teilen". (Alle Charaktere eines WoW-Kontos teilen diese Daten ohnehin.)

## 1.12.0 - 2026-10-20

### Farmen
- **Sammelpunkte auf der Weltkarte:** jeder Zuwachs eines markierten Gegenstands merkt sich, wo du warst; die Karte zeigt dort kleine Gegenstandssymbole (Einstellung "Sammelpunkte auf der Weltkarte anzeigen"). Rechtsklick auf eine Zeile der Farm-Anzeige öffnet die Karte dort oder löscht die Punkte.
- **Beste Orte:** der Tab "Farmen" vergleicht deine Farmgebiete aus dem Verlauf - Gold pro Stunde im Schnitt, Anzahl der Sitzungen, die beste mit Wegpunkt zu ihrem Startpunkt.
- **Sitzungsziele:** Rechtsklick auf den Titel der Farm-Anzeige -> Gold oder Zeit für jede Sitzung (z. B. 10.000 g oder 60 Minuten); Fortschritt unten in der Farm-Anzeige und eine Meldung beim Erreichen.
- **Zusammenfassung im Chat posten:** dasselbe Menü schickt Gebiet, Zeit, Gold (pro Stunde) und deine besten Gegenstände an Gruppe, Gilde oder Sagen.

### Notizen & Orte
- **Notizen zu Spielern, NPCs und deinen Charakteren:** Maus über einen Spieler oder NPC (oder ins Ziel nehmen) und die Notiz-Taste drücken; die Notiz steht in seinem Tooltip. NPC-Notizen gelten für jedes Exemplar dieses NPCs. Deine eigenen Charaktere: "Neue Notiz ..." im Tab "Notizen" oder `/el charnote [Name]`. Neue Gruppe "Spieler und NPCs" im Tab.
- **Respawn-Timer an Pins:** gib einem Rare- oder Schatz-Pin in seinem Fenster eine Respawn-Zeit und mach Strg-Klick auf ihn, wenn du es getötet oder geplündert hast - der Pin wird rot und du bekommst eine Meldung, sobald es wieder da ist (auch nach einem Relog).
- **Notiz im Auktionshaus:** ein Gegenstand mit Notiz im Verkaufsfeld des Auktionshauses zeigt seine Notiz in einem kleinen Feld neben dem Fenster.

## 1.11.4 - 2026-10-20

### Farmen
- Behoben: die Sitzungsuhr der Farm-Anzeige sprang manchmal um 2 Sekunden (und zeigte andere Sekunden doppelt); sie zählt jetzt jede Sekunde.

## 1.11.3 - 2026-10-20

### Farmen
- **Notiz aus der Farm-Anzeige:** Rechtsklick auf eine Zeile (Farm- und Questen-Ansicht) -> "Notiz hinzufügen ..." / "Notiz bearbeiten ..." öffnet das Notizfenster des Moduls Notizen für diesen Gegenstand.
- Behoben: hast du einen Gegenstand nicht mehr verfolgt, verschwand das in dieser Sitzung Gefarmte, statt zurück in "Weitere Beute" zu wandern.

### Notizen & Orte
- **Woher erbeutete Gegenstände stammen:** Gegenstände aus Beute und Questbelohnungen (ab Rar, einstellbar) werden mit Gebiet, Koordinaten, Datum und dem Namen der toten Kreatur im Ziel bzw. der Quest gemerkt - im Tooltip ("Erbeutet: ..." / "Questbelohnung: ...") und in der neuen Gruppe "Beute und Quests" im Tab "Notizen".
- **Erinnerungen:** Betrittst du ein Gebiet mit Pins, sagt dir der Chat, wie viele es dort gibt; kommst du einem Erledigen-, Rare- oder Schatz-Pin nahe, erscheint sein Kommentar auf dem Bildschirm (Abstand einstellbar, höchstens alle 15 Minuten).
- **Pins auf der Minikarte** (Maus darüber: Kommentar, Klick: Wegpunkt; dreht sich mit einer drehenden Minikarte).
- **Erledigt:** Shift-Klick auf einen Pin der Weltkarte (oder "Erledigt" in seinem Fenster) - er wird auf den Karten blass und erinnert nicht mehr; "Erledigte Pins ausblenden" nimmt sie von den Karten.
- **Export als /way-Zeilen:** "/way ..." im Tab "Notizen" (oder `/el way export`) zeigt alle Pins oder die deines Gebiets als /way-Zeilen zum Kopieren für Freunde oder deine Gilde.

## 1.11.2 - 2026-10-20

### Notizen & Orte
- **Warnung beim Verkauf eines Gegenstands mit Notiz:** Meldung in der Bildschirmmitte, die Notiz im Chat und ein Fenster zum Zurückkaufen - der Verkauf wird nie blockiert. In den Einstellungen wählbar, für welche Gegenstände: nicht gebunden (standardmäßig an, auch beim Anlegen gebunden und "kriegsmeutengebunden bis zum Anlegen"), seelengebunden, kriegsmeutengebunden. Zum Verkauf markierte oder auf "immer verkaufen" gesetzte Gegenstände warnen nicht.

## 1.11.1 - 2026-10-20

### Notizen & Orte
- **Mit deinen anderen Konten geteilt:** bei eingeschalteter Konten-Synchronisierung erscheinen Pins, Gegenstandsnotizen und Käufe deines anderen WoW-Kontos auch hier - auf der Karte, in Tooltips und im Tab "Notizen", nur lesbar und mit dem Konto gekennzeichnet. Einstellung: "Meine Notizen mit meinen anderen Konten teilen".
- **Pins auf Kontinent- und Weltkarte:** Pins eines Gebiets erscheinen (etwas kleiner) auch, wenn die Karte den Kontinent oder die Welt zeigt (abschaltbar).
- **/way-Zeilen importieren** (TomTom-Format, z. B. von Wowhead): "/way importieren" im Tab "Notizen" oder `/el way` - eine oder viele Zeilen einfügen; Gebietsnamen, `#Karten-ID` und Dezimalkomma werden verstanden, vorhandene Pins übersprungen.
- **Notiz-Symbol in den Taschen:** Gegenstände mit Notiz zeigen oben rechts einen kleinen Zettel (Standard-Taschen, Bank, Baganator); die Verkaufsmünze hat Vorrang.

## 1.11.0 - 2026-10-20

### Notizen & Orte (neues Modul)
- **Karten-Pins mit Kommentar:** Alt+Klick auf die Weltkarte setzt dort einen Pin - Art wählen (Notiz, Händler, Schatz, Rare, Erledigen) und Kommentar schreiben. Maus über den Pin zeigt den Kommentar, Linksklick setzt einen Wegpunkt, Rechtsklick bearbeitet oder löscht ihn. "Meine Position pinnen" (oder `/el pin`) pinnt deinen Standort.
- **Gegenstandsnotizen:** Maus über einen Gegenstand und Notiz-Taste drücken (Standard `STRG-N`), oder einen Gegenstand auf "Gegenstandsnotiz" im Tab "Notizen" ziehen. Eine Notiz gilt für die Gegenstandsart, kann deinen aktuellen Ort speichern und steht im Tooltip. Gegenstände mit Notiz werden nicht mehr automatisch als Plunder, altes Essen oder bekanntes Spielzeug verkauft (markierte schon).
- **Käufe werden gemerkt:** jeder bei einem Händler gekaufte Gegenstand wird mit Händler, Gebiet, Koordinaten, Datum und Preis gespeichert und steht in seinem Tooltip - auch Monate später weißt du noch, woher er stammt.
- **Tab "Notizen"** im Easylife-Fenster (`/el notes`): Pins, Gegenstandsnotizen und Käufe, durchsuchbar nach Kommentar, Gebiet, Gegenstand oder Händler, mit Filter "Dieses Gebiet"; "Karte" öffnet den Ort auf der Weltkarte.

## 1.10.7 - 2026-10-19

### Farmen
- **Questbelohnungen im Tab "Farmen":** eigene Gruppe mit dem Verbleib jeder Belohnung (in den Taschen, verkauft, angelegt, verbraucht); dort stehen sie nicht mehr zusätzlich unter weiterer Beute. In der Questen-Ansicht zeigt die Zusammenfassung des Tabs Quests, Questgold und EP pro Stunde.
- **Chat-Zusammenfassung** nach Neu starten nennt bei Quest-Sitzungen jetzt auch Quests, Questgold, verkaufte Belohnungen und EP.

## 1.10.6 - 2026-10-19

### Farmen
- **Knopf Questen / Farmen** unten rechts in der Farm-Anzeige wechselt zwischen den beiden Ansichten (ersetzt das kleine Symbol neben dem Titel).
- Behoben: die Sitzungsuhr der Farm-Anzeige konnte bei "läuft" stehen bleiben (bis etwas erbeutet wurde) - auch nach Pause und Start.
- Behoben: EP konnten direkt nach dem Einloggen falsch gezählt werden, wenn das Spiel die EP noch nicht geladen hatte.

## 1.10.5 - 2026-10-19

### Farmen
- **Questen-Ansicht:** Klick auf das kleine Symbol neben dem Titel der Farm-Anzeige wechselt (jeder Charakter merkt sich seine Ansicht). Sie zeigt Questgold, verkaufte Questbelohnungen, Rohgold und übrige Händlereinnahmen, Quests pro Stunde und - unterhalb der Höchststufe - EP pro Stunde und die Zeit bis zur nächsten Stufe. In dieser Ansicht zählt Questgold zum Gesamtwert pro Stunde; mit "Automatisch starten" startet das Abgeben einer Quest eine Sitzung.
- **Questbelohnungen:** Gegenstände von Quests werden erkannt und in der Questen-Ansicht mit ihrem Verbleib gelistet - verkauft (Münze), angelegt (Haken), verbraucht oder verschickt (grau) oder noch in deinen Taschen; Zurückkaufen macht einen Verkauf rückgängig. In der Farm-Ansicht sind sie unter "Weitere Beute" markiert.
- Behoben: Ausrüstung, die du ablegst, erscheint nicht mehr unter "Weitere Beute".
- Questgegenstände für Questziele erscheinen nicht mehr unter "Weitere Beute". Der Verlauf speichert auch Quests, Questgold, verkaufte Belohnungen und EP.
- Knopf **Wegpunkt** im Verlauf: führt zurück zum Startpunkt einer Sitzung - TomToms Pfeil, falls installiert, sonst Blizzards Kartenmarkierung mit Navigation. Sitzungen, die in einer Instanz gestartet sind, haben keine Koordinaten und keinen Knopf.

## 1.10.4 - 2026-10-18

### Farmen
- **Verlauf:** jede beendete Sitzung (Neu starten, oder länger als 30 Minuten ausgeloggt) wird mit dem Startpunkt (Zone, Unterzone, Koordinaten), Zeit, Gegenständen, Gold und Gold pro Stunde gespeichert - im Tab "Farmen", um Farmgebiete zu vergleichen. Der Chat zeigt beim Ende einer Sitzung eine kurze Zusammenfassung.
- **Ziele:** Rechtsklick auf einen markierten Gegenstand -> "Ziel festlegen" (20 bis 1000 oder eine beliebige Menge im Besitz). Die Farm-Anzeige zeigt "120/200" mit Fortschrittsbalken, der Tooltip die Restzeit bei deinem aktuellen Tempo, und beim Erreichen erscheint ein Hinweis.
- **Taschenplatz** oben in der Farm-Anzeige (gelb bei wenig, rot an der Schwelle) und einmal eine Warnung beim Farmen, wenn er knapp wird (Einstellungen -> Farmen -> "Taschenplatz").
- **Item-Sets:** markierte Gegenstände unter einem Namen speichern und mit einem Klick wechseln - Rechtsklick auf den Titel der Farm-Anzeige oder "Item-Sets" im Tab "Farmen".
- Optionen: Farm-Anzeige im Kampf ausblenden, oder in Dungeons, Schlachtzügen, Schlachtfeldern und Arenen (standardmäßig an); "Im Besitz" kann alle deine Charaktere zählen (braucht Syndicator, das zu Baganator gehört).

## 1.10.3 - 2026-10-18

### Farmen
- **Rohgold:** Gold, das du während einer Sitzung erbeutest, wird gezählt. Gold aus Post, Auktionshaus, Handel und Questbelohnungen zählt nicht.
- **Händlereinnahmen:** was du während einer Sitzung bei Händlern verdienst, zählt getrennt - außer Verkäufen deiner markierten Farm-Gegenstände, die schon als "Gefarmt" zählen.
- Die Fußzeile der Farm-Anzeige zeigt "Gefarmt · Rohgold · Händler" und den **Gesamtwert mit Gold pro Stunde**. Beides lässt sich unter Einstellungen -> Farmen -> "Gold" abschalten (standardmäßig an).

## 1.10.2 - 2026-10-18

### Behoben
- Der X-Knopf schließt das Easylife-Fenster wieder.

### Farmen
- **Rechtsklick auf eine Zeile** der Farm-Anzeige: Gegenstand **nicht mehr verfolgen**, Gegenstand der weiteren Beute verfolgen oder **beim nächsten Händlerbesuch verkaufen** - alle Stapel in deinen Taschen bekommen die Verkaufsmarkierung des Händler-Moduls (gesperrte Gegenstände werden übersprungen). Eine Münze am Symbol zeigt die Markierung; "Nicht verkaufen" entfernt sie wieder.
- **Immer verkaufen** im selben Menü, mit der üblichen Reichweite (dieser Charakter, alle Charaktere des Kontos, alle Konten): die Regel landet in der Verkaufsliste und wird synchronisiert, auch künftige Beute wird verkauft. Ein Münzstapel am Symbol zeigt es; "Nicht mehr immer verkaufen" entfernt die Regel. Zahlt das Auktionshaus deutlich mehr als der Händler (über das 3-fache, Auctionator oder TSM), warnt der Chat.
- Der Tab "Farmen" bietet dasselbe: sein Knopf "Verkaufen" öffnet das Verkaufsmenü und zeigt den Stand ("Markiert", "Immer").

## 1.10.1 - 2026-10-18

### Farmen
- **Weitere Beute:** die Farm-Anzeige listet alles andere, was du in einer Sitzung bekommst, unter "Weitere Beute (n)" (Klick zum Ein-/Ausblenden), mit Menge und Goldwert. **[+]** verfolgt einen Gegenstand sofort, und was du in dieser Sitzung schon erbeutet hast, wird übernommen - auch beim Markieren per Taste. Der Tab "Farmen" listet alles mit einem Knopf "Verfolgen".

## 1.10.0 - 2026-10-18

### Farmen
- Neues Modul: markiere die Gegenstände, die du farmst, per Taste (Standard **STRG-F**, Maus über den Gegenstand in Taschen oder Bank). Markierte Gegenstände zeigen eine Taschenuhr im Taschenplatz und eine Tooltip-Zeile.
- **Farm-Anzeige:** ein kleines verschiebbares Fenster mit, je markiertem Gegenstand, wie viele du besitzt, wie viele du in dieser Sitzung **gefarmt** hast (beginnt bei null - was schon in deinen Taschen war, zählt nie), pro Stunde und Gold pro Stunde, dazu die Sitzungszeit. Knöpfe **Start/Pause** und **Neu starten** unten; die Spalte "Im Besitz" lässt sich ausblenden. Werte pro Stunde erscheinen nach 1 Minute Farmzeit. Ein Klick auf den Titel öffnet den neuen Tab "Farmen" im Easylife-Fenster.
- Die Sitzung startet mit dem ersten markierten Gegenstand, den du bekommst, und pausiert nach einigen Minuten ohne Beute von selbst; Leerlauf zählt nicht. Käufe, Post, Handel und Verschieben in die Bank werden nicht gezählt.
- Goldwerte aus Auctionator oder TradeSkillMaster, falls installiert, sonst der Händlerpreis. `/el farm` blendet die Anzeige ein/aus, `/el farm reset` startet eine neue Sitzung.

## 1.9.0 - 2026-10-14

### Neu
- **Überschneidende Addons:** einige Sekunden nach dem Einloggen listet Easylife installierte Addons auf, die dasselbe tun (Vendor, Inventory Guardian, Scrap, Peddler, AutoVendor), und bietet an, sie zu deaktivieren - für diesen Charakter oder alle Charaktere des WoW-Kontos - mit einem Klick und Neuladen.
- Bei **TitanRepair** werden nur Auto-Reparatur und Grau-Verkauf ausgeschaltet; die Haltbarkeitsanzeige in Titan Panel bleibt.
- "Später" fragt beim nächsten Einloggen erneut, "Nicht mehr fragen" hört für diese Addons auf. Einstellungen -> Easylife -> "Überschneidende Addons" ("Jetzt prüfen") oder `/el addons` öffnet die Prüfung jederzeit. Ersetzt den alten einmaligen Chat-Hinweis.

## 1.8.0 - 2026-10-14

### Neu
- Händler: **niedrigstufiges Essen und Trinken verkaufen** - Essen, dessen benötigte Stufe weit unter deinem Charakter liegt (einstellbar, Standard 10 Stufen). Essen ohne Stufenanforderung wird behalten.
- Händler: **bereits bekannte Spielzeuge verkaufen** (seelengebundene Spielzeuge, die schon in deiner Spielzeugkiste sind).
- Händler: **höchstens 12 Gegenstände pro Besuch**, damit sich jeder Verkauf zurückkaufen lässt; der Rest wird beim nächsten Besuch verkauft. Standardmäßig an.
- Der Tooltip zeigt, wenn altes Essen oder ein bekanntes Spielzeug verkauft wird. Essen und Spielzeuge sind standardmäßig aus; einschalten unter "Händler" -> "Plunder verkaufen". Damit ersetzt Easylife das Addon Vendor.

## 1.7.0 - 2026-10-14

### Neu
- Gegenstände deiner **Ausrüstungssets** sind automatisch geschützt wie gesperrte Gegenstände, ohne sie von Hand zu sperren. Der Tooltip nennt das Set. Abschaltbar unter "Schutz".
- Gesperrte Gegenstände sind vor dem **Verschrotten** geschützt: sie werden wieder aus der Verschrottungsmaschine genommen, und Verschrotten wird gestoppt, solange einer drin liegt.
- Gesperrte Gegenstände sind vor dem **Entzaubern** geschützt: solange der Entzaubern-Zeiger aktiv ist, sind sie in den Taschen ausgegraut und können nicht gewählt werden.
- Beide neuen Schutzarten haben eigene Schalter und Ausnahmen pro Gegenstand ("Optionen" im Tab "Gesperrt"). Damit ersetzt Easylife das Addon Inventory Guardian.

## 1.6.1 - 2026-10-14

### Geändert
- Kompatibel mit Spielversion 12.1.5.

## 1.6.0 - 2026-10-14

### Mehrere Konten
- Neues Modul: nimmt **Gruppeneinladungen**, **geteilte Quests** und (optional) **Beschwörungen** deiner eigenen Charaktere automatisch an - dieses Konto und deine vertrauten synchronisierten Konten. Bei Fremden erscheint weiter der normale Dialog.

## 1.5.0 - 2026-10-06

### Neu
- Gesperrte Gegenstände sind auch vor **Post** und **Handel** geschützt: standardmäßig dürfen sie nur an eigene Charaktere gehen (dieses Konto und vertraute synchronisierte Konten); ein geschützter Gegenstand wird wieder aus dem Handelsfenster genommen.
- Schutz-Einstellungen pro Aktion (Verkaufen, Zerstören, Auktionshaus, Post, Handel) mit **Ausnahmen pro Gegenstand** in beide Richtungen: im Tab "Gesperrt" kann "Optionen" jede Aktion für einen einzelnen Gegenstand oder eine Sperr-Regel erlauben oder verhindern. Ausnahmen stehen im Tooltip.
- `/el debug` zeigt im Chat, was Easylife entscheidet und warum; `/el debug log` öffnet die Ausgabe zum Kopieren in einem Fenster - hilfreich für Fehlermeldungen.

## 1.4.0 - 2026-10-06

### Neu
- Gesperrte Gegenstände lassen sich nicht mehr ins Auktionshaus einstellen - im Standard-Auktionshaus, in Auctionator und TradeSkillMaster (Einstellung unter Schutz).

## 1.3.0 - 2026-10-06

### Neu
- Der Rahmen um **Immer verkaufen**-Gegenstände zeigt, wo die Regel gilt: orange = ein Charakter, lila = dieses Konto, blau = alle Konten.
- Tooltips von Gegenständen mit Regel **Immer verkaufen** oder Sperr-Regel nennen den Geltungsbereich (z. B. "alle Charaktere dieses Kontos").

### Geändert
- Die Easylife-Zeilen in Gegenstands-Tooltips sind durch eine Leerzeile vom Text des Spiels abgesetzt und stehen gesammelt als ein Block.

## 1.2.0 - 2026-10-06

### Neu
- Zahnrad-Symbol in der Titelleiste des Fensters: öffnet die Einstellungen zum aktuellen Tab.

## 1.1.0 - 2026-10-06

### Geändert
- Ein **Easylife-Fenster** mit Tabs am unteren Rand - **Gesperrt**, **Verkaufsliste** und **Neuigkeiten** - statt einzelner Fenster.
- Das Minikarten-Symbol öffnet das Fenster direkt mit dem zuletzt genutzten Tab; die Listen-Tasten und Befehle öffnen ihren Tab und schließen das Fenster bei erneutem Drücken.

## 1.0.0 - 2026-10-06

### Gegenstandssperre
- Gegenstände per Taste sperren (Standard **STRG-H**): Maus über den Gegenstand im Charakterfenster, in den Taschen oder der Bank und Taste drücken; nochmal drücken entsperrt.
- Gesperrte Gegenstände sind geschützt: Beim Händler aufgenommene werden zurückgelegt, versehentlich verkaufte sofort zurückgekauft (oder ein Fenster bietet es an), Zerstören wird verhindert und beim Ablegen erscheint eine Warnung.
- **Art sperren**: jeden Gegenstand einer Art sperren, für diesen Charakter, alle Charaktere dieses Kontos oder alle deine Konten.
- Schloss-Symbole in den Standard-Taschen, der Bank und Kriegsmeutenbank, im Charakterfenster und in Baganator, dazu eine Tooltip-Zeile.
- Fenster **Gesperrte Gegenstände**: gesperrte Gegenstände aller Charaktere mit Suche, Charakterfilter, einklappbaren Gruppen und "Entsperren"-Knopf; Sperren von Gegenständen, die es nicht mehr gibt, lassen sich mit einem Klick entfernen.

### Händler
- Verkauft grauen Plunder automatisch und repariert die Ausrüstung, mit Gildengold zuerst, wenn erlaubt. SHIFT beim Öffnen eines Händlers überspringt das einmal.
- Gegenstände per Taste für den nächsten Händler markieren (Standard **STRG-J**); aus einer Markierung eine Regel **Immer verkaufen** machen, für diesen Charakter, dieses Konto oder alle deine Konten.
- Fenster **Verkaufsliste** mit markierten Gegenständen und Regeln; Münz-Symbole in den Taschen, mit orangem Rahmen für "Immer verkaufen".
- Die Chat-Meldung zeigt das tatsächlich erhaltene Gold.
- Gesperrte Gegenstände werden nie verkauft oder markiert.

### Konten-Synchronisierung
- Teilt Listen und Regeln zwischen deinen WoW-Konten desselben Battle.net-Kontos, solange beide online sind, ohne Einrichtung.
- Jedes andere Konto muss einmal bestätigt werden; Daten werden nur mit vertrauten Konten ausgetauscht. Der Knopf "Synchronisieren" holt Änderungen sofort.

### Allgemein
- Minikarten-Symbol und Eintrag im Addon-Menü; Linksklick öffnet die Fenster, Rechtsklick die Einstellungen.
- Einstellungen mit Erklärungen auf jeder Seite, Module lassen sich ein- und ausschalten.
- Deutsch und Englisch.
- Fenster **Neuigkeiten** nach Updates (dieses Fenster).
