# Audit Methodik – Google Chrome

## Phase 1 – Informationssammlung

- Chrome-Version prüfen
- Installierte Profile lokalisieren
- Policies prüfen (`chrome://policy`, Registry)

## Phase 2 – Konfigurations-Audit

Überprüfung sicherheitsrelevanter Einstellungen:

- Registry / GPO / Policies
- `Preferences` JSON in Profilen
- Erweiterungslisten prüfen

## Phase 3 – Risiko-Bewertung

- Hoch: kritische Sicherheitslücken
- Mittel: Datenschutz/Tracking-Schwächen
- Niedrig: optionale Hardening-Einstellungen

## Phase 4 – Reporting

- Findings mit Status, Risiko, Empfehlung
