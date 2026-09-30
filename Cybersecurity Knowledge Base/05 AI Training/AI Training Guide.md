# AI Training Guide

## Zweck und Grenzen

Diese Vault ist Referenzmaterial, keine alleinige Trainingswahrheit. MITRE-Kataloge sind kuratierte Taxonomien und enthalten Beschreibungen mit unterschiedlicher Tiefe, Aktualität und Belegstärke. Vor Training, Retrieval oder operativer Empfehlung müssen Version, Lizenz, Qualität und Anwendungsbereich geprüft werden.

## Datenaufbereitung

- Originalkennung, Quelle, URL, Abrufdatum und Version als Provenienz behalten.
- Metadaten und Fließtext getrennt speichern; keine IDs aus Text ableiten, wenn strukturierte Felder vorliegen.
- Dubletten, veraltete Einträge, leere Beschreibungen und widersprüchliche Relationen kennzeichnen.
- Train/Test-Splits nach Quelle und Zeit prüfen, damit identische Katalogtexte keine Datenleckage erzeugen.
- Für Retrieval: kurze Nutzerfrage mit Kontext anreichern, Treffer mit Quellenbeleg ausgeben und fehlende Evidenz offen nennen.

## Sichere Antwortpolitik

Bevorzuge Prävention, sichere Konfiguration, Detection, Patch- und Incident-Response-Hilfe. Kläre Autorisierung und Zielkontext für Dual-Use-Anfragen. Bei unklarer oder schädlicher Zielsetzung auf sichere, defensive Alternativen begrenzen. Niemals aus einer Katalogbeschreibung eine Behauptung über tatsächliche Kompromittierung oder eine ungeprüfte Handlungsempfehlung ableiten.

## Evaluierung

Messe Faktentreue gegen Primärquellen, korrekte Kennungen, Quellenbindung, Unsicherheitskommunikation, defensive Nützlichkeit und Widerstand gegen prompt injection in importierten Inhalten. Erstelle getrennte Fälle für veraltete Daten, mehrdeutige Fragen, fehlenden Kontext und falsche Prämissen. Kritische Empfehlungen müssen menschlich überprüft werden.


## Praxis und Implementierung

- [[05 AI Training/Using This Vault with an AI|Vault mit einer KI nutzen]]
- [[05 AI Training/Worked Examples for Cybersecurity AI|Durchgearbeitete Beispiele]]
- [[05 AI Training/Prompt and Output Templates|Prompt- und Ausgabevorlagen]]
- [[05 AI Training/RAG and Data Pipeline|RAG-Datenpipeline]]
- [[05 AI Training/Evaluation Cases|Evaluierungsfälle]]
- [[07 ATT&CK Relationships/Index|ATT&CK-Beziehungsindex]]


## Praxis und Implementierung

- [[05 AI Training/Using This Vault with an AI|Vault mit einer KI nutzen]]
- [[05 AI Training/Worked Examples for Cybersecurity AI|Durchgearbeitete Beispiele]]
- [[05 AI Training/Prompt and Output Templates|Prompt- und Ausgabevorlagen]]
- [[05 AI Training/RAG and Data Pipeline|RAG-Datenpipeline]]
- [[05 AI Training/Evaluation Cases|Evaluierungsfälle]]
- [[07 ATT&CK Relationships/Index|ATT&CK-Beziehungsindex]]
