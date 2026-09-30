---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0604"
target_object: "T1046"
stix_relationship_id: "relationship--1d1cc2e5-ef43-4b36-9077-3b173e03d254"
---
# Relationship 6708: S0604 — uses → T1046

**Source object:** [[01 ATT&CK/S0604 - Industroyer|S0604: Industroyer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Industroyer](https://attack.mitre.org/software/S0604) uses a custom port scanner to map out a network.(Citation: ESET Industroyer)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d1cc2e5-ef43-4b36-9077-3b173e03d254`.
