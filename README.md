# Dreieck Gebäudemanagement GmbH

Aktueller Website-Stand aus Sites mit 14 Seiten, eigenständigen Leistungsunterseiten und acht KI-gekennzeichneten Leistungsbildern.

## Veröffentlichung

GitHub Actions lädt den Inhalt von `dist/` über den bestehenden Hetzner-Zugang direkt in dessen Wurzelverzeichnis. Benötigte Repository-Secrets: `HETZNER_HOST`, `HETZNER_USER`, `HETZNER_PORT`, `HETZNER_PASSWORD`. Kein TARGET-Secret.

Der Workflow startet nach Änderungen an `main`. Ein manueller Verbindungstest ist unter Actions verfügbar. Bestehende Dateien außerhalb des Website-Exports werden nicht gelöscht. Startseite und eine Bilddatei werden nach der Übertragung zum Vergleich zurückgelesen.

Impressum und Datenschutz enthalten weiterhin die vorhandenen Entwürfe. Das aktuell übernommene goldene Logo trägt den Schriftzug Facility Management GmbH.
