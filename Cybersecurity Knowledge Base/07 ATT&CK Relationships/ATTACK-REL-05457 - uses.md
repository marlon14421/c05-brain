---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0401"
target_object: "T1008"
stix_relationship_id: "relationship--73a5da20-5358-4da8-8417-020a7dec52cb"
---
# Relationship 5457: S0401 — uses → T1008

**Source object:** [[01 ATT&CK/S0401 - Exaramel for Linux|S0401: Exaramel for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Exaramel for Linux](https://attack.mitre.org/software/S0401) can attempt to find a new C2 server if it receives an error.(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73a5da20-5358-4da8-8417-020a7dec52cb`.
