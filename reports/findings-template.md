# Google Chrome Audit Findings

## Zusammenfassung

| ID   | Kategorie           | Erwartet | Beobachtet | Status | Risiko |
|------|-------------------|----------|------------|--------|--------|
| GC-01 | Safe Browsing     | Enabled  | Disabled   | ✘      | Hoch |
| GC-03 | Passwort Autofill | Disabled | Enabled    | ✘      | Mittel |

---

### GC-01 – Safe Browsing

**Erwartet:** Aktiviert  
**Beobachtet:** Deaktiviert  
**Status:** Nicht konform  
**Risikostufe:** Hoch  
**Empfehlung:** Setze `SafeBrowsingEnabled = 1` via Registry oder GPO

---

### GC-03 – Passwort Autofill

**Erwartet:** Deaktiviert  
**Beobachtet:** Aktiviert  
**Status:** Nicht konform  
**Risikostufe:** Mittel  
**Empfehlung:** Setze `PasswordManagerEnabled = 0` via Registry / Policy
