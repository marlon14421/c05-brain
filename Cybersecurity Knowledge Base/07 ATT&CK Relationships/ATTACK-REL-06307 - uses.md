---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "S0154"
stix_relationship_id: "relationship--2b5ece1f-a678-40af-b4e3-1787ae3de343"
---
# Relationship 6307: G1046 — uses → S0154

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) operations include the use of [Cobalt Strike](https://attack.mitre.org/software/S0154).(Citation: Microsoft Storm-1811 2024)(Citation: rapid7-email-bombing)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b5ece1f-a678-40af-b4e3-1787ae3de343`.
