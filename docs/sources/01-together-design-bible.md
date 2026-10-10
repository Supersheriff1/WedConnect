# together · Design Bible

**Status:** verbindlicher visueller Standard für die TFP-Plattform  
**Version:** 1.0 · 10. Oktober 2026  
**Designrichtung:** Cream & Gold, warm, elegant, editorial und gut lesbar

Diese Bible friert den aktuellen Cream-&-Gold-Stand als Referenz für alle bestehenden und neuen Bereiche der App ein. Neue Screens, Zustände und Komponenten folgen diesen Regeln. Eine Abweichung ist nur eine bewusste, dokumentierte Designentscheidung.

## 1. Gestalterisches Ziel

together soll sich wie eine hochwertige, ruhige Hochzeitsplattform anfühlen. Die Oberfläche gibt den Hochzeitsbildern und Portfolios Raum. Creme und Sand bilden die warme Bühne; Goldocker setzt sparsame Akzente; dunkles Braun sorgt für lesbare Texte. Karten sind großzügig, weich gerundet und zurückhaltend beschattet.

Die Referenz ist die zuletzt freigegebene Cream-&-Gold-App mit Montserrat und Libre Caslon Text. Das dunkle Aubergine- und das Korallrot-Design sind keine gültigen App-Standards mehr.

## 2. Farbpalette

| Design-Token | Wert | Verwendung |
|---|---|---|
| `paper` | `#F4E8D1` | Warmer Seitenhintergrund |
| `paper-soft` | `#F8F2E8` | Leichte Flächenvariation, wenn nötig |
| `surface` | `#FFFDF8` | Karten, Dialoge und Eingabeflächen |
| `surface-warm` | `#FFFAF1` | Kopfzeile, mobile Navigation, helle Overlays |
| `ink` | `#2D211B` | Überschriften und Haupttext |
| `text-secondary` | `#55483C` | Beschreibungen, Labels und erklärender Text |
| `text-muted` | `#6F6258` | Zurückhaltende Metadaten; nur auf hellen Flächen |
| `gold` | `#D3A451` | Primäre Aktionen, aktive Zustände, wichtige Marker |
| `gold-dark` | `#75532B` | Goldene Schrift und Icons auf hellen Flächen |
| `sand` | `#F2E4C9` | Chips, dezente Infoboxen, sekundäre Flächen |
| `border` | `#E5D8C4` | Karten-, Feld- und Trennlinien |
| `success` | `#557E5E` | Erfolg und bestätigte Zustände |
| `alert` | `#A93F38` | Fehler oder wichtige Warnungen, sparsam eingesetzt |

Gold ist ein Flächenakzent und keine Textfarbe für kleine Schrift. Auf Goldflächen steht dunkler Text (`#2E2116`), nie weißer Text. Sekundärtext bleibt dunkel genug, um auf Creme und Weiß klar lesbar zu sein.

### Kontrastreferenz

Die folgenden berechneten Kontrastverhältnisse gelten für die aufgeführten Farbpaare:

| Vordergrund / Hintergrund | Verhältnis | Einsatz |
|---|---:|---|
| `#2D211B` / `#F4E8D1` | 12.87:1 | Haupttext auf Creme |
| `#2D211B` / `#FFFDF8` | 15.36:1 | Haupttext auf Karten |
| `#55483C` / `#F4E8D1` | 7.28:1 | Sekundärtext auf Creme |
| `#55483C` / `#FFFDF8` | 8.69:1 | Sekundärtext auf Karten |
| `#2E2116` / `#D3A451` | 6.84:1 | Beschriftung auf Goldbutton |
| `#513B20` / `#F2E5CC` | 8.44:1 | Text auf Sand-Chip |

Diese Werte sind Referenzwerte der reinen Farbpaare. Bei Transparenz, Bildern, Hover-Zuständen oder neuen Farben muss der tatsächlich gerenderte Zustand erneut geprüft werden.

## 3. Typografie

| Einsatz | Schrift |
|---|---|
| Seitentitel, Kartentitel, redaktionelle Überschriften | **Libre Caslon Text**, regulär 400 |
| Navigation, Fließtext, Formulare, Buttons, Labels, Metadaten | **Montserrat** |
| UI-Bedienelemente | Montserrat Medium 500 bis SemiBold 600; primäre Aktionen 700 |

Überschriften bleiben ruhig und groß genug, UI-Schrift klar und funktional. Buttons verwenden keine kursiven oder dekorativen Schnitte. Lange Lesetexte erhalten ausreichenden Zeilenabstand. Schrift darf auf mobilen Ansichten nicht so weit verkleinert werden, dass Bedienung oder Lesbarkeit leiden.

### Verbindliche mobile Größen

Die gewählte Referenz ist **Uber-Niveau**. Sie gilt für alle mobilen App-Bereiche:

| Element | Größe |
|---|---:|
| Standard- und Lesetext | 16 px |
| Navigation, Formulare, Buttons und Nachrichten | 16 px |
| Navigation unten | 13 px |
| Sekundärangaben und Metadaten | 14 px |
| Chips und Badges | 13 px |
| Kartenüberschriften | 23 px |
| Abschnittsüberschriften | 23 px |
| Seitentitel | 34 px |
| Primärbuttons | mindestens 50 px hoch |

Diese Vorgabe ersetzt die vorherigen kleineren Mobilwerte. Sie verändert Schrift und nötige Bedienabstände; Cream-&-Gold-Farben, Bildsprache und Komponentenstil bleiben unverändert.

## 4. Flächen, Raster und Bildsprache

- Seitenhintergrund: warmes Creme; Karten: fast weiß mit feinem Sandrahmen.
- Großzügige Innenabstände und klare Trennung zwischen Abschnitten.
- Karten haben konsistente, weiche Radien; Schatten bleiben leicht und diffus.
- Fotografien sind der visuelle Schwerpunkt. Bilder werden nicht durch starke Farbfilter oder dunkle Flächen überdeckt.
- Portfolio- und Profilbilder mit `object-fit: cover`; wichtige Motive und Gesichter beim Zuschnitt sichtbar halten.
- Desktop nutzt eine klare Inhaltsfläche mit optionaler Seitenleiste. Mobile Ansichten priorisieren Inhalte und verwenden die freigegebene untere Navigation.
- Verläufe sind höchstens sehr subtil und dürfen Kontrast, Bildwirkung oder Lesbarkeit nicht beeinträchtigen.

## 5. Komponentenregeln

### Navigation

Helle Creme- beziehungsweise Weißflächen. Aktiver Menüpunkt mit warmer Sandfläche und dunkler goldbrauner Beschriftung. Icons und Labels müssen gemeinsam verständlich sein; Zähler erscheinen als ruhige, gut lesbare Chips.

### Buttons

- **Primär:** Goldfläche `#D3A451`, dunkle Schrift `#2E2116`, klare Form und gut sichtbarer Fokuszustand.
- **Sekundär:** weiße oder cremefarbene Fläche, dunkler Text, feiner Rahmen.
- **Dezent:** helle Sandfläche mit dunkler Schrift.
- Alle Buttons verwenden Montserrat mit mindestens 500, in der Regel 600 oder 700.
- Hover, Fokus, gedrückt und deaktiviert müssen unterscheidbar sein. Deaktivierte Zustände dürfen nicht wie aktiv wirken.

### Karten und Tags

Weiße Karten mit dünnem Sandrahmen. Tags und Badges stehen auf Sand oder warmem Weiß und verwenden dunkle Schrift. Keine blasse Schrift auf Gold oder gesättigten Flächen.

### Formulare

Weiße Eingabeflächen, dunkler Eingabetext, deutlich sichtbare Beschriftung und ein goldener Fokusrahmen. Platzhalter ersetzen keine Feldbeschriftung. Fehlerzustände verwenden verständlichen Text und einen zusätzlichen visuellen Hinweis, nicht nur eine Farbänderung.

### Profile und Portfolio

Profilname und wichtige Titel in Libre Caslon Text. Angaben, Konditionen und Aktionen in Montserrat. Bilder erhalten Vorrang. Konditionen, Leistungsumfang und Nutzungsrechte bleiben auf hellen, klar lesbaren Flächen.

## 6. Nachrichtenansicht

Der Nachrichtenbereich gehört vollständig zum Cream-&-Gold-System:

- Gesprächsfläche: weiße Karte mit feinem Sandrahmen.
- Eingehende Nachricht: helles Sandbeige (`#F2E8D8`) mit dunklem Text.
- Gesendete Nachricht: warmes Goldbeige (`#EAD5A9`) mit dunklem Text; Gold bleibt hell genug, damit der Text klar lesbar ist.
- Nachrichten sind links und rechts eindeutig ausgerichtet und haben großzügige Innenabstände.
- Eingabe: weiße Fläche, dunkler Text, gut lesbarer Platzhalter und sichtbarer Gold-Fokusrahmen.
- Senden-Aktion: primärer Goldbutton mit dunkler Beschriftung.
- Hinweise zu Absprachen und Nutzungsrechten stehen in einer hellen Infobox mit dunkler Schrift.
- Mobile Darstellung hält Eingabe und Senden gut bedienbar und lässt den Nachrichtenverlauf ausreichend Platz.

Kein violetter Chat-Hintergrund, keine dunklen Nachrichtenblasen und keine schwach kontrastierenden Texte auf Rot- oder Goldflächen.

## 7. Bewegung und Match

Animationen unterstützen Orientierung und Feedback. Ein Match darf mit einer kurzen, eleganten Einblendung, einem Herz-Pop und wenigen goldenen Lichtpunkten hervorgehoben werden. Bewegung bleibt kurz und ruhig; sie darf die Bedienung nicht blockieren. Bei `prefers-reduced-motion` werden nicht notwendige Bewegungen reduziert oder abgeschaltet.

## 8. Barrierearme Umsetzung und Qualitätscheck

Vor dem Freigeben eines neuen Screens oder einer Änderung prüfen:

1. Ist der Hintergrund hell und warm, mit dunkler, klar lesbarer Schrift?
2. Bleiben Goldflächen auf Aktionen und kleine Akzente beschränkt, mit dunkler Schrift darauf?
3. Sind Buttons, Links, Fokus, deaktivierte Zustände und Fehlermeldungen eindeutig erkennbar?
4. Sind Schriftfamilien und Hierarchie konsistent mit Montserrat und Libre Caslon Text?
5. Funktionieren Karten, Bilder, Formulare und Nachrichten auf Desktop und Mobilgeräten?
6. Sind Kontraste der tatsächlich gerenderten Zustände ausreichend, auch über Bildern und bei Transparenz?
7. Bleibt die TFP-Funktion verständlich: gegenseitiges Interesse erzeugt das Match; die Nachricht dient der gemeinsamen Klärung von Umfang, Preis und Nutzungsrechten.

## 9. Verbindlichkeit und Pflege

Diese Datei ist die zentrale Designreferenz für together. Neue Screens und Komponenten übernehmen die Tokens und Muster aus dieser Bible. Änderungen an Farbpalette, Typografie oder Grundstil werden zuerst hier dokumentiert und danach konsistent in der App umgesetzt. Einzelne Screens führen keine eigenen Farbwelten oder abweichenden Typografien ein.

## 10. Aktueller App-Stand

Die HTML-Demo enthält Paar- und Fotograf:innenansicht, Profile und Portfolio-Vorschauen, Entdecken und Filtern, gegenseitige Likes mit animiertem Match, Nachrichten, Profilbearbeitung und lokale Speicherung im Browser. Diese Funktionen verwenden denselben Cream-&-Gold-Standard.
