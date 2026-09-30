---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1073"
target_object: "T1057"
stix_relationship_id: "relationship--f0a36615-b3eb-47d5-8a2a-9d7429643a0a"
---
# Relationship 6061: S1073 — uses → T1057

**Source object:** [[01 ATT&CK/S1073 - Royal|S1073: Royal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Royal](https://attack.mitre.org/software/S1073) can use `GetCurrentProcess` to enumerate processes.(Citation: Cybereason Royal December 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0a36615-b3eb-47d5-8a2a-9d7429643a0a`.
