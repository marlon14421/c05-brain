# Defensive Playbooks

## 1. Asset- und Bedrohungskontext

Dokumentiere Zweck, Eigentümer, Datenklassen, Vertrauensgrenzen, externe Abhängigkeiten und kritische Geschäftsprozesse. Erstelle Bedrohungshypothesen, keine unbelegten Zuschreibungen. Nutze ATT&CK als Verhaltensvokabular.

## 2. Schwachstellen-Triage

Erfasse betroffene Version, Exposition, Erreichbarkeit, Berechtigungen, Auswirkung, vorhandene Schutzmaßnahmen und Belege. CWE hilft bei der Ursachenklassifikation. Priorisiere nach realem Risiko und Behebbarkeit; ein CWE-Eintrag ist keine CVE und kein Exploitnachweis.

## 3. Detection Engineering

Formuliere eine überprüfbare Hypothese, nenne Telemetriequellen, erwartete Signale, legitime Gegenbeispiele, Datenschutzfolgen und Reaktionsschritte. Teste Regeln in einer kontrollierten Umgebung mit synthetischen oder autorisierten Daten. Messe Abdeckung, Fehlalarme und Blindstellen.

## 4. Incident Response

Sichere Beweise, protokolliere Zeit und Herkunft, begrenze Schaden nach genehmigtem Verfahren, bewahre Beweisketten und prüfe Wiederherstellung. Trenne Beobachtung, Schlussfolgerung und Unsicherheit.

## 5. Sicheres Testen

Nur ausdrücklich autorisierte Systeme und vereinbarte Testfenster verwenden. Bevorzuge lokale Laborumgebungen, Mockdaten und nicht-destruktive Checks. Keine produktiven Daten exfiltrieren oder Kontrollen ohne Freigabe umgehen. Abbruchkriterien und Kontaktweg vorher definieren.
