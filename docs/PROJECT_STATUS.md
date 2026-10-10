# WedConnect: Projektziel und aktueller Stand

**Stand:** 10. Oktober 2026  
**Status:** visuell freigegebener Prototyp, noch kein produktives Produkt  
**Eingefrorene Demo:** `baseline/2026-10-10-pairing-demo`  
**Aktuelle Design-Dokumentation:** `docs/wedconnect-design-bible-v1.0`

## Projektziel

WedConnect bringt Hochzeitspaare und Hochzeitsfotografen zusammen, wenn Hochzeit, Ort, Bildsprache und Erwartungen zueinander passen. Fotografen können passende echte Hochzeiten entdecken und ihre Arbeit mit ausdrücklicher Zustimmung des Paars für ihr Portfolio nutzen. Paare können Stil und Erfahrung vergleichen und mit passenden Fotografen ins Gespräch kommen.

Ein Interesse ist unverbindlich. Ein Match bedeutet gegenseitiges Interesse und eröffnet das Gespräch über Umfang, Preis, Ablauf und Bildrechte. Die Demo soll keine gestellten Hochzeiten als echte Reportagen ausgeben und keine Portfolio- oder Werbenutzung ohne gesonderte Zustimmung nahelegen.

## Produktprinzipien

- Beide Seiten entscheiden selbst, wo sie Interesse zeigen.
- Ein Match entsteht erst bei beidseitigem Interesse.
- Echte Hochzeiten und authentische fotografische Arbeiten stehen im Mittelpunkt.
- Umfang, Preis, Ablauf und Rechte werden vor einer Zusammenarbeit transparent besprochen.
- Das Paar erhält standardmäßig volle Nutzungsrechte. Eine Portfolio- oder Werbenutzung durch den Fotografen braucht eine zusätzliche, ausdrückliche Vereinbarung.

## Eingefrorener Prototyp

Die direkt im Browser öffnungsfähige Datei [`prototype/index.html`](../prototype/index.html) vereint Website und App-Vorschau in einer HTML-Datei. CSS, JavaScript und die Hero-Illustration sind eingebettet.

- Startseite mit der Headline „Wo Hochzeitspaare und Fotografen sich finden.“
- Informationsseiten für Hochzeitspaare und Fotografen
- navigierbare App-Demo mit Rollenwahl, Demo-Profilen, Filtern, Interessensaktionen, Match-Rückmeldung sowie Nachrichten-, Profil- und Kontobereichen
- dunkles Pairing-Design mit Goldakzenten und zentriertem Verbindungselement
- responsive Navigation und fließende Seitenränder für schmale, mittlere und breite Viewports

Profile, Konten, Matches, Nachrichten und Aktionen sind Beispieldaten beziehungsweise lokale Simulationen. Die Hero-Abbildung ist als KI-Illustration gekennzeichnet.

## Design- und Markenstatus

Der aktuelle Produktname ist **WedConnect**. Die aktuelle visuelle Referenz ist [`DESIGN_BIBLE.md`](DESIGN_BIBLE.md), WedConnect Design Bible v1.0. Sie ersetzt Cream-&-Gold-Vorgaben aus der früheren Together Design Bible.

Die Projekt- und Brand-Voice-Bibles unter `docs/sources/` dokumentieren den historischen Together-Stand und bleiben als unveränderte Quellen erhalten. Sie müssen noch separat auf WedConnect und den aktuellen Produktstand konsolidiert werden.

## Technischer Status

- Eine statische HTML-Datei ohne Framework, Build-Prozess oder installierbare Abhängigkeiten.
- CSS und JavaScript sind eingebettet; die Illustration ist in der Datei enthalten.
- Google Fonts werden online geladen. Ohne Netzverbindung greifen lokale Schrift-Fallbacks.
- HTML-/JavaScript-Syntax wurde geprüft. Eine vollständige Sichtprüfung auf realen Geräten und in mehreren Browsern ist noch offen.
- Es gibt keine produktive Authentifizierung, Datenbank, Nutzerkonten, Moderation, echte serverübergreifende Matches, Ende-zu-Ende-verschlüsselten Chat, Zahlungsabwicklung oder dauerhafte Medienablage.

## Nächste sinnvolle Schritte

1. Die aktuelle Design Bible auf typischen Desktop-, Tablet- und Mobilbreiten visuell gegen die Demo prüfen.
2. Project Bible und Brand-Voice-Bible auf WedConnect und Pairing konsolidieren.
3. TFP-Rahmen, Preis/Umfang, Rechtevereinbarung und Match-Ablauf verbindlich festlegen.
4. Erst danach entscheiden, welche Demo-Flows in ein Backend und echte Nutzerkonten überführt werden.
