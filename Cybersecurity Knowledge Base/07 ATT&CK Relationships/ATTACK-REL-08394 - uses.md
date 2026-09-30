---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1023"
target_object: "T1567.002"
stix_relationship_id: "relationship--1cfb7192-6136-4946-8ee1-498f59125b9b"
---
# Relationship 8394: S1023 — uses → T1567.002

**Source object:** [[01 ATT&CK/S1023 - CreepyDrive|S1023: CreepyDrive]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CreepyDrive](https://attack.mitre.org/software/S1023) can use cloud services including OneDrive for data exfiltration.(Citation: Microsoft POLONIUM June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1cfb7192-6136-4946-8ee1-498f59125b9b`.
