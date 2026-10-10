# WedConnect: Projektziel und eingefrorener Stand

**Stand:** 10. Oktober 2026  
**Status:** freigegebener visueller und inhaltlicher Startpunkt, noch kein produktives Produkt  
**Baseline-Branch:** `baseline/2026-10-10-pairing-demo`

## Projektziel

WedConnect bringt Hochzeitspaare und Hochzeitsfotografen zusammen, wenn Hochzeit, Ort, Bildsprache und Erwartungen zueinander passen. Fotografen können passende echte Hochzeiten entdecken und ihre Arbeit mit ausdrücklicher Zustimmung des Paars für ihr Portfolio nutzen. Paare können Stil und Erfahrung vergleichen und mit passenden Fotografen ins Gespräch kommen.

Ein Interesse ist unverbindlich. Ein Match bedeutet gegenseitiges Interesse und eröffnet das Gespräch über Umfang, Preis, Ablauf und Bildrechte. Die Demo soll keine gestellten Hochzeiten als echte Reportagen ausgeben und keine Portfolio- oder Werbenutzung ohne gesonderte Zustimmung nahelegen.

## Produktprinzipien

- Beide Seiten entscheiden selbst, wo sie Interesse zeigen.
- Ein Match entsteht erst bei beidseitigem Interesse.
- Echte Hochzeiten und authentische fotografische Arbeiten stehen im Mittelpunkt.
- Umfang, Preis, Ablauf und Rechte werden vor einer Zusammenarbeit transparent besprochen.
- Das Paar erhält standardmäßig volle Nutzungsrechte. Eine Portfolio- oder Werbenutzung durch den Fotografen braucht eine zusätzliche, ausdrückliche Vereinbarung.

## Was in diesem Stand enthalten ist

Die direkt im Browser öffnungsfähige Datei [`prototype/index.html`](../prototype/index.html) vereint Website und App-Vorschau in einer HTML-Datei. Sie enthält eingebettetes CSS, JavaScript und die Hero-Illustration.

- Startseite mit der Headline „Wo Hochzeitspaare und Fotografen sich finden.“
- Informationsseiten für Hochzeitspaare und Fotografen
- navigierbare App-Demo mit Rollenwahl, Demo-Profilen, Filtern, Interessensaktionen, Match-Rückmeldung, Nachrichten-, Profil- und Kontobereichen
- Pairing-Design mit dunkler Oberfläche, warmen Goldakzenten, klaren Karten und responsiven Navigations- und Layoutregeln
- durchgängige Seitenränder mit fließender Anpassung an schmale und mittlere Viewports

Die Profilbilder, Konten, Matches, Nachrichten und Aktionen sind Beispieldaten beziehungsweise lokale Simulationen. Die Abbildung im Hero ist als KI-Illustration gekennzeichnet.

## Technischer Status

- Eine einzelne statische HTML-Datei, ohne Framework, Build-Prozess oder installierbare Abhängigkeiten.
- CSS und JavaScript sind in der Datei enthalten; die Illustration ist eingebettet.
- Google Fonts werden online geladen. Ohne Netzverbindung greifen lokale Schrift-Fallbacks.
- HTML-/JavaScript-Syntax wurde geprüft. Eine vollständige Sichtprüfung auf realen Geräten und in mehreren Browsern ist noch offen.
- Es gibt keine produktive Authentifizierung, Datenbank, Nutzerkonten, Moderation, echte serverübergreifende Matches, Ende-zu-Ende-verschlüsselten Chat, Zahlungsabwicklung oder dauerhafte Medienablage.

## Design- und Markenstatus

Der aktuelle Projektname ist **WedConnect**. Die mitgelieferten Design-, Projekt- und Voice-Bibles stammen noch aus der Together-Phase und bleiben als unveränderte Quellen erhalten. Sie beschreiben zum Teil eine frühere Cream-&-Gold-Gestaltung. Der hier eingefrorene aktuelle Prototyp verwendet das neuere dunkle Pairing-Design mit Goldakzenten. Diese Abweichung ist sichtbar dokumentiert und muss in einer nächsten konsolidierten Design Bible bereinigt werden.

## Nächste sinnvolle Schritte

1. Die Baseline auf typischen Desktop-, Tablet- und Mobilbreiten visuell prüfen und Layoutkorrekturen als neue Version dokumentieren.
2. Brand-, Voice- und Design-Bibles auf den Namen WedConnect und den aktuellen Pairing-Stand konsolidieren.
3. Produktentscheidungen zu TFP-Rahmen, Preis/Umfang, Rechtevereinbarung und Match-Ablauf verbindlich festlegen.
4. Erst danach entscheiden, welche Demo-Flows in ein Backend und echte Nutzerkonten überführt werden.
