---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1027.013"
stix_relationship_id: "relationship--83e30b05-5658-4cc3-9bac-500ea852e655"
---
# Relationship 7882: S0483 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) has utilzed encrypted binaries and base64 encoded strings.(Citation: Juniper IcedID June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83e30b05-5658-4cc3-9bac-500ea852e655`.
