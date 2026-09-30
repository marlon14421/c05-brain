---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1183"
target_object: "T1020"
stix_relationship_id: "relationship--f7539748-0911-4a98-a98f-f512d1424d85"
---
# Relationship 7640: S1183 — uses → T1020

**Source object:** [[01 ATT&CK/S1183 - StrelaStealer|S1183: StrelaStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrelaStealer](https://attack.mitre.org/software/S1183) automatically sends gathered email credentials following collection to command and control servers via HTTP POST.(Citation: DCSO StrelaStealer 2022)(Citation: IBM StrelaStealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7539748-0911-4a98-a98f-f512d1424d85`.
