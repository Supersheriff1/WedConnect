# together · Project Bible

**Version:** 1.0  
**Stand:** 10. Oktober 2026  
**Status:** Eingefrorener Arbeitsstand  
**Geltungsbereich:** Produktidee, Website, zusammengeführte HTML-Demo und Regeln für die Weiterarbeit

Diese Project Bible hält den derzeitigen inhaltlichen und technischen Arbeitsstand fest. Sie ergänzt die visuelle Referenz, ersetzt sie aber nicht. Wenn sich diese Bible und die Design Bible zu visuellen Details unterscheiden, gilt die Design Bible.

## 1. Projektziel

together bringt Hochzeitspaare und Hochzeitsfotograf:innen zusammen, wenn die Hochzeit, der fotografische Stil und die Erwartungen beider Seiten zueinander passen. Ein Interesse ist zunächst unverbindlich. Ein Match soll gegenseitiges Interesse bedeuten; erst danach folgt das persönliche Gespräch über Umfang, Preis, Ablauf und Bildrechte.

Die Plattform soll echte Hochzeiten und eigenständige fotografische Arbeiten ermöglichen. Sie soll keine gestagten Shootings als echte Hochzeiten darstellen und keine Veröffentlichung ohne klare Vereinbarung voraussetzen.

## 2. Eingefrorener Stand und Quelle der Wahrheit

### Aktuelle Übergabedatei

`/together-komplett.html` ist die aktuelle, zusammengeführte und direkt öffnungsfähige HTML-Demo. Sie vereint die öffentliche Website und App-Ansichten in einer Datei. CSS, JavaScript und das Hero-Foto sind eingebettet. Die Datei wurde syntaktisch geprüft und enthält vier getrennt anwählbare Bereiche:

- `home` – allgemeine Erklärung und Einstieg
- `photographers` – eigene Informationsseite für Fotograf:innen
- `couples` – eigene Informationsseite für Hochzeitspaare
- `app` – interaktive Demo

Die öffentliche Navigation schaltet zwischen Seitenansichten um; die Zielgruppeninformationen sind keine Ankerabschnitte innerhalb einer langen Seite. Das together-Logo führt zurück zur Startseite. Die Demo kann über die Navigation oder passende Handlungsbuttons geöffnet werden.

### Maßgebliche Designreferenz

`project_sources/01-together-design-bible.md` ist die verbindliche visuelle Referenz. Sie legt Cream & Gold, Typografie, mobile Mindestgrößen, Komponenten, Bildregeln, Chatgestaltung und Match-Bewegung fest.

### Vorherige mehrteilige Arbeitsfassung

`together-site-v3/` enthält die zuvor gepflegte Websitefassung mit `index.html`, `fotografen.html`, `hochzeitspaare.html` und `app.html` sowie deren ältere `PROJECT-BIBLE.md`. Diese Dateien bleiben als vorheriger Arbeitsstand erhalten. Für Änderungen am eingefrorenen Ein-Datei-Artefakt ist `together-komplett.html` die direkte Basis. Die Dateien aus `together-site-v3/` dürfen nicht unbemerkt als aktueller Ein-Datei-Stand ausgegeben werden.

Andere HTML-Dateien im Projektverzeichnis sind frühere Entwürfe, Stilversuche oder Vergleichsstände. Sie sind keine aktive Quelle der Wahrheit.

## 3. Zielgruppen und Nutzen

### Fotograf:innen

Fotograf:innen benötigen ein aussagekräftiges Portfolio, das ihren eigenen Stil zeigt und passende Kund:innen anspricht. Es kann lange dauern, dieses Portfolio durch reguläre Hochzeitsbuchungen aufzubauen.

Übliche Alternativen und ihre Nachteile:

1. **Portfolio über reguläre Aufträge aufbauen:** authentische Hochzeiten, aber es dauert oft lange, bis ausreichend vielfältige und repräsentative Arbeiten vorliegen.
2. **Eigene Shootings organisieren:** Brautkleider, Blumen, Papeterie, Location und Models müssen selbst organisiert werden. Das kostet Zeit und Nerven; die Bilder zeigen ein geplantes Shooting und keine echte Hochzeit.
3. **Styled Wedding buchen:** kann an hochwertigen Locations stattfinden, kostet teilweise mehrere tausend Euro und liefert gestagte Bilder. Mehrere teilnehmende Fotograf:innen können dieselben inszenierten Motive erhalten. Auch hier dauert es, bis daraus ein umfassendes Portfolio entsteht.

**together-Angebot:** passende echte Hochzeiten nach Stil, Location, Termin und Rahmenbedingungen entdecken. Fotograf:innen entscheiden selbst, wo sie Interesse zeigen. Eine Portfoliofreigabe ist vorab transparent zu besprechen und muss vom Paar ausdrücklich eingeräumt werden.

Wichtig: together verspricht nicht, dass ein einzelnes Match automatisch ein vollständiges Portfolio erzeugt oder eine konkrete Buchung garantiert.

### Hochzeitspaare

Paare sollen vor der Anmeldung und Auswahl Informationen zu Service und Preisen bekommen. Im Produkt stehen für sie vor allem im Vordergrund:

- bisherige Erfahrung und Referenzen der Fotograf:innen
- vollständige, aussagekräftige Portfolioarbeiten
- visuelle Bildsprache und Passung zu den eigenen Vorstellungen
- transparente Angaben zu Umfang, Preis und Ablauf
- verständliche Regelung der Bild- und Nutzungsrechte

Paare erhalten standardmäßig volle Nutzungsrechte an ihren Hochzeitsfotos. Eine zusätzliche Veröffentlichung durch Fotograf:innen, etwa im Portfolio oder zur Eigenwerbung, braucht eine gesonderte, ausdrückliche Vereinbarung.

## 4. Website-Inhalte und Navigation

Die Website erklärt den Dienst vor einer Registrierung und führt in die passende App-Rolle.

- **Startseite:** gemeinsamer Zweck, Überblick über Ablauf, Wahl der Zielgruppe und Einstieg in die Demo.
- **Für Fotograf:innen:** Portfolio-Herausforderung, drei herkömmliche Wege samt Aufwand, together-Lösung, Ablauf, Portfoliofreigabe und Preisinformation.
- **Für Hochzeitspaare:** Auswahl anhand von Erfahrung, Portfolio und Referenzen, Bildrechte, Ablauf und Preisinformation.
- **So funktioniert together:** Teil der Startseite beziehungsweise über das Logo erreichbar; kein eigener Menüpunkt.
- **Anmeldung:** Rolle vor dem Fortfahren auswählen; mindestens E-Mail und Google als gewünschte Optionen. Die Demo zeigt beide Wege, implementiert aber keine echte Authentifizierung.
- **Preise:** Vor Produktivstart müssen echte, abgestimmte Tarife und Services veröffentlicht werden. Die Demo darf keine verbindlichen oder erfundenen Preise suggerieren. Beispielpreise in Demo-Profilkarten sind Beispieldaten.

Zielgruppenbereiche bleiben in Text, Nutzenargumenten und CTAs getrennt. Keine Fotograf:innen-Argumente in die Paarseite mischen und umgekehrt, außer bei gemeinsam erforderlichen Prozess- oder Rechteinformationen.

## 5. Umfang der HTML-Demo

Die eingefrorene Demo bietet folgende lokale beziehungsweise simulierte Oberflächen:

- Rollenwahl für Hochzeitspaar oder Fotograf:in
- Übersichtsbereich, Entdecken/Filtern, Profilkarten, Matches, Nachrichten, Profil/Portfolio und Kontoeinstellungen
- Interessen zeigen und gesendetes Interesse mit Bestätigungsdialog zurückziehen
- kurzes, eigens gestaltetes Match-Feedback mit Herz-Pop und reduzierter Bewegung bei `prefers-reduced-motion`
- Demo-Chat mit Beispielnachrichten und sichtbarem Hinweis auf den Schutzstatus
- Profilfelder, lokale Speicherung eines Namens und lokale Bildvorschau beim Upload
- Auswahl von Foto-Dateien; Bildstreifen kann horizontal durchgesehen werden
- Einstellungsdialoge für Pro/Zahlung, Hilfe, Einladungen, Rechtliches, Datenschutz, Abmeldung und Kontolöschung
- responsive Desktop- und Mobilnavigation

Demo-Funktionen dienen der Darstellung und dem Durchklicken. Sie begründen keinen produktiven Dienst und keine Backend-Funktion.

## 6. Verbindliche Anforderungen für die Produktumsetzung

| Bereich | Soll-Verhalten |
|---|---|
| Kontotyp | Bei Anmeldung genau eine Rolle wählen: Fotograf:in oder Hochzeitspaar. Rollenwechsel später über Konto/Profileinstellungen ermöglichen, falls Produktregeln es zulassen. |
| Anmeldung | E-Mail und gängige OAuth-Anbieter, insbesondere Google; sichere Wiederherstellung des Kontos. |
| Fotograf:innenprofil | Erfahrung, Stil, Region, Verfügbarkeit, Leistungen/Preisrahmen, vollständige Portfolioarbeiten, Referenzen und benötigte Nutzungsfreigaben. |
| Paarprofil | Termin, Location, Region, Gästezahl, Hochzeitsrahmen, Stilwünsche, Inspirations-/Referenzbilder und klare Rechtepräferenz. |
| Interessen | Rücknahme eines bereits versendeten Interesses nur nach expliziter Bestätigung. |
| Match | Erst bei gegenseitigem Interesse; kurze kreative Animation, keine Tinder-artige Swipe-Match-Inszenierung; `prefers-reduced-motion` beachten. |
| Bildrechte | Paar hat standardmäßig volle Nutzungsrechte. Portfolio-/Marketingnutzung der Fotograf:innen muss ausdrücklich, verständlich und separat vereinbart werden. |
| Uploads | Fotos vor dem Speichern einpassen oder zuschneiden können. Profilbildansichten und Portfolio sollen den vollständigen Bildausschnitt zeigen, wo ausdrücklich gewünscht; Seitenverhältnisse und Vorschaudarstellung klar handhaben. |
| Galerie | Profilfotos mit Links-/Rechts-Swipe oder gleichwertiger zugänglicher Navigation; Tastatur und Screenreader mitdenken. |
| Chat | Produktiver Chat muss Ende-zu-Ende-verschlüsselt sein, sodass Betreiber und Dritte nicht mitlesen können. Eine UI-Beschriftung oder Transportverschlüsselung allein reicht nicht. |
| Kontoverwaltung | Abmelden, Impressum/Rechtliches, Datenschutz, Hilfe, Freunde einladen/App empfehlen, Pro Account/Zahlung und Kontolöschung. Löschung muss produktiv Daten gemäß Recht und Aufbewahrungspflichten behandeln. |
| Responsive UX | Klare visuelle Hierarchie, gut auffindbare Aktionen, keine horizontale Seitenscrollerei, ausreichend große mobile Schrift und Touch-Ziele. |

## 7. Designvorgaben

Die vollständigen Designregeln stehen in `01-together-design-bible.md`. Kernpunkte:

- Cream-&-Gold-Palette: Papier `#F4E8D1`, Oberfläche `#FFFDF8`, Gold `#D3A451`, dunkle Schrift `#2D211B`.
- Libre Caslon Text für redaktionelle Überschriften; Montserrat für UI und Fließtext.
- Warmes, ruhiges, bildorientiertes Erscheinungsbild mit klarer Hierarchie, großzügigem Raster und hellen Karten.
- Goldflächen erhalten dunkle Beschriftung. Dunkle Aubergine- und Korall-Designsysteme sind nicht gültig.
- Mobile App-Text grundsätzlich mindestens 16 px, Primäraktionen mindestens 50 px hoch; die Design Bible enthält die vollständige Größentabelle.
- Bilder erhalten Vorrang und werden nicht durch starke Filter überlagert. Vorgaben zu vollständiger Darstellung und Zuschnitt pro Komponente beachten.
- Chatblasen: eingehend Sandbeige, gesendet warmes Goldbeige, jeweils mit dunkler Schrift.

Ein globaler CSS-Override, der frühere Designexperimente zurückbringt oder die aktuelle Gestaltung flächig ersetzt, ist zu vermeiden. Neue visuelle Entscheidungen zuerst gegen die Design Bible prüfen und dokumentieren.

## 8. Nicht produktiv umgesetzt

Zum eingefrorenen Stand gehören keine echten produktiven Dienste für:

- Authentifizierung, Google OAuth oder andere Anbieter
- Backend, Nutzerkonten, dauerhafte Speicherung oder Moderation
- echtes Matching über verschiedene Nutzerkonten
- Ende-zu-Ende-verschlüsselten Chat
- kostenpflichtigen Pro-Account, Zahlungsabwicklung oder Rechnungen
- verbindliche Tarife oder veröffentlichungsfähige Rechtstexte
- dauerhafte Medienablage und serverseitige Bildverarbeitung
- echte Löschung und Export personenbezogener Daten

Der Chat in der HTML-Demo zeigt ausdrücklich einen Hinweis, dass er nicht Ende-zu-Ende-verschlüsselt ist. Diese Grenze darf bei Vorschau oder Beschreibung nicht verschleiert werden.

### Bekannte Lücken der eingefrorenen Demo

- Das Match wird im Prototyp teilweise durch einen Demo-Shortcut ausgelöst. Es bildet keine echte gegenseitige Zustimmung zweier getrennter Konten ab.
- E-Mail- und Google-Anmeldung sind Auswahlbuttons beziehungsweise Simulationen; es findet keine echte Authentifizierung statt.
- Der Upload zeigt lokale Vorschauen. Eine echte Bildbearbeitung mit interaktivem Zuschnitt und Einpassungswahl ist noch nicht umgesetzt.
- Die Profilkarten verwenden teilweise einen angeschnittenen Bildausschnitt. Das widerspricht dem Produktwunsch, den vollständigen Bildausschnitt anzuzeigen, und muss vor einer Freigabe als Lösung für diese Anforderung angepasst werden.
- Profile, Filter, Nachrichten und Löschabläufe sind Demonstrationsdaten und keine zuverlässige serverseitige Funktion.
- Die Darstellung wurde technisch auf HTML-/JavaScript-Syntax geprüft. Eine vollständige Sichtprüfung in mehreren echten Browsern und Bildschirmgrößen ist noch offen.

## 9. Änderungs- und Freigabeprozess

Vor Änderungen:

1. Diese Project Bible und `01-together-design-bible.md` lesen.
2. Die betroffene Datei und den konkreten Bereich feststellen. Bei der konsolidierten Demo `together-komplett.html` verwenden.
3. Bestehendes Verhalten und Design notieren, bevor die Änderung erfolgt.
4. Nur den erforderlichen Umfang ändern; keine unbeteiligten Bereiche neu gestalten.
5. HTML- und JavaScript-Syntax, interne Navigation, Bilddarstellung und Desktop-/Mobilansicht prüfen.
6. Bei Änderungen an Funktionstexten gegen die getrennten Bedürfnisse der zwei Zielgruppen prüfen.
7. Project Bible und Versionsstand aktualisieren, wenn Umfang, Architektur, Inhalte oder Designregeln sich ändern.
8. Einen benannten, funktionierenden Rückkehrpunkt erhalten. Keine ältere Datei stillschweigend zur neuen Quelle machen.

## 10. Änderungsprotokoll

| Version | Datum | Stand |
|---|---|---|
| 1.0 | 10.10.2026 | Ein-Datei-Website und Demo eingefroren; Rollen, Zielgruppenbotschaften, Portfolioargumentation, Rechte, Demo-Umfang und Produktgrenzen dokumentiert. |
