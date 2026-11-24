# Business-Concierge: Homepage

Eigene Website für den Business-Concierge: empfohlene Tools und Partner für
KI, Automatisierung und Digitalisierung im Mittelstand.

Der Concierge war bis 24.11.2026 Teil von schmal-unternehmensberatung.de
(Seiten /concierge/ und /empfehlung/) und wird hier als eigenes Angebot
aufgebaut. Das Design folgt, sobald die Designidee steht.

**Dieses Repository ist öffentlich. Hier liegen nur öffentliche Inhalte.**
Keine Verträge, Provisionssätze, Partnerkonditionen, internen Notizen oder
Kundendaten einchecken.

## Inhalt

| Pfad | Was |
|---|---|
| `inhalte/empfehlungen.ts` | Alle Empfehlungen mit Gruppe, Kurztext und Einsatzzweck |
| `inhalte/datenschutz-abschnitt.md` | Bisheriger Datenschutz-Wortlaut zu Partnerlinks und Empfehlungsformular |
| `vorlage/Concierge.astro` | Bisherige Darstellung (Astro-Komponente) als Ausgangspunkt |
| `vorlage/ConciergeHinweis.astro` | Bisheriger Teaser auf der Startseite |
| `vorlage/seite-concierge.astro`, `vorlage/seite-empfehlung.astro` | Bisherige Seiten, inkl. eingebettetem Jotform-Formular „Empfehlung anfragen“ |

Die Vorlagen stammen aus einem Astro-Projekt und verweisen auf Dateien
(Layouts, Icons, Hilfsfunktionen), die hier noch nicht liegen. Sie dienen als
Referenz für Texte, Struktur und Transparenzhinweis.

## Pflichten für die neue Seite

- Transparenzhinweis zu Provisionen gut sichtbar („Für einige Empfehlungen
  erhalte ich eine Provision. Ihr Preis ändert sich dadurch nicht.“)
- Partnerlinks mit `rel="sponsored"`
- Eigenes Impressum und eigene Datenschutzerklärung
