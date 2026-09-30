---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0023"
target_object: "T1027.011"
stix_relationship_id: "relationship--8a6bfa36-adff-402d-9913-be2e45bc22aa"
---
# Relationship 7596: S0023 — uses → T1027.011

**Source object:** [[01 ATT&CK/S0023 - CHOPSTICK|S0023: CHOPSTICK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.011 - Fileless Storage|T1027.011: Fileless Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CHOPSTICK](https://attack.mitre.org/software/S0023) may store RC4 encrypted configuration information in the Windows Registry.(Citation: FireEye APT28)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a6bfa36-adff-402d-9913-be2e45bc22aa`.
