---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1170"
target_object: "T1102.002"
stix_relationship_id: "relationship--2c713523-db2e-4ef6-9a2e-3913bc31051d"
---
# Relationship 9042: S1170 — uses → T1102.002

**Source object:** [[01 ATT&CK/S1170 - ODAgent|S1170: ODAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ODAgent](https://attack.mitre.org/software/S1170) can use the Microsoft Graph API to access an attacker-controlled OneDrive account and retrieve payloads and backdoor commands.(Citation: ESET OilRig Downloaders DEC 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c713523-db2e-4ef6-9a2e-3913bc31051d`.
