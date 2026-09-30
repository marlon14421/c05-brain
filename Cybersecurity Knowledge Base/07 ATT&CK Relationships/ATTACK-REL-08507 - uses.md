---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0083"
target_object: "T1547"
stix_relationship_id: "relationship--9c63a942-eb05-401b-a49a-39dc05ef1dd9"
---
# Relationship 8507: S0083 — uses → T1547

**Source object:** [[01 ATT&CK/S0083 - Misdat|S0083: Misdat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547 - Boot or Logon Autostart Execution|T1547: Boot or Logon Autostart Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Misdat](https://attack.mitre.org/software/S0083) has created registry keys for persistence, including `HKCU\Software\dnimtsoleht\StubPath`, `HKCU\Software\snimtsOleht\StubPath`, `HKCU\Software\Backtsaleht\StubPath`, `HKLM\SOFTWARE\Microsoft\Active Setup\Installed. Components\{3bf41072-b2b1-21c8-b5c1-bd56d32fbda7}`, and `HKLM\SOFTWARE\Microsoft\Active Setup\Installed Components\{3ef41072-a2f1-21c8-c5c1-70c2c3bc7905}`.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c63a942-eb05-401b-a49a-39dc05ef1dd9`.
