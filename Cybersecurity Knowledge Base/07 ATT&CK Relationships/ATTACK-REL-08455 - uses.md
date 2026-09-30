---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0132"
target_object: "T1490"
stix_relationship_id: "relationship--2d090e9d-f9fb-4f73-99df-0e17a7489adb"
---
# Relationship 8455: S0132 — uses → T1490

**Source object:** [[01 ATT&CK/S0132 - H1N1|S0132: H1N1]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[H1N1](https://attack.mitre.org/software/S0132) disable recovery options and deletes shadow copies from the victim.(Citation: Cisco H1N1 Part 2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d090e9d-f9fb-4f73-99df-0e17a7489adb`.
