# CIS-ähnliche Controls – Google Chrome

| ID      | Kategorie                     | Beschreibung                                      | Erwartet                                | Prüfmethode |
|---------|-------------------------------|-------------------------------------------------|----------------------------------------|-------------|
| GC-01   | Safe Browsing                 | Schutz vor Malware/Phishing                      | Enabled                                | chrome://policy / Registry |
| GC-02   | HTTPS Enforcement             | HTTPS-only Mode                                  | Enabled                                | chrome://policy / Registry |
| GC-03   | Password Autofill             | Deaktivieren Passwortspeicherung                 | Disabled                               | chrome://policy / Preferences |
| GC-04   | Extension Management          | Nur zugelassene Erweiterungen                     | Whitelist Only                          | Registry / Policies |
| GC-05   | Data Collection               | Telemetrie / Usage Data deaktivieren             | Disabled                               | chrome://policy / Registry |
| GC-06   | Pop-ups / Downloads           | Restriktionen für Pop-ups und Downloads          | Enabled / Restricted                    | Registry / Preferences |
| GC-07   | Safe Plugins / Flash          | Unsichere Plugins deaktiviert                     | Disabled                               | Preferences / Policy |
| GC-08   | Proxy / Network Settings      | Sichere Proxy-Einstellungen erzwingen            | Policy enforced                          | Registry / Policies |
| GC-09   | Certificates / HTTPS          | CRL/OCSP Check aktiv                              | Enabled                                | Preferences / Policy |
| GC-10   | Updates                       | Auto-update aktiviert                              | Enabled                                | Registry / Preferences |
