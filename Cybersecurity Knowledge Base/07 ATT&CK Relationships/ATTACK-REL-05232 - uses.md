---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1075"
target_object: "T1566.001"
stix_relationship_id: "relationship--da37b8c0-7006-43f9-aebb-44ae51a54dd0"
---
# Relationship 5232: S1075 — uses → T1566.001

**Source object:** [[01 ATT&CK/S1075 - KOPILUWAK|S1075: KOPILUWAK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KOPILUWAK](https://attack.mitre.org/software/S1075) has been delivered to victims as a malicious email attachment.(Citation: Mandiant Suspected Turla Campaign February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da37b8c0-7006-43f9-aebb-44ae51a54dd0`.
