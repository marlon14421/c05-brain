---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0532"
target_object: "T1497.001"
stix_relationship_id: "relationship--5473acfd-2cb3-45a8-97cb-c3962c606f1e"
---
# Relationship 5975: S0532 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0532 - Lucifer|S0532: Lucifer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lucifer](https://attack.mitre.org/software/S0532) can check for specific usernames, computer names, device drivers, DLL's, and virtual devices associated with sandboxed environments and can enter an infinite loop and stop itself if any are detected.(Citation: Unit 42 Lucifer June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5473acfd-2cb3-45a8-97cb-c3962c606f1e`.
