---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0020"
target_object: "T1480.001"
stix_relationship_id: "relationship--3d661b40-6ebf-470f-a675-142f86b6c649"
---
# Relationship 5195: G0020 — uses → T1480.001

**Source object:** [[01 ATT&CK/G0020 - Equation|G0020: Equation]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.001 - Environmental Keying|T1480.001: Environmental Keying]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Equation](https://attack.mitre.org/groups/G0020) has been observed utilizing environmental keying in payload delivery.(Citation: Kaspersky Gauss Whitepaper)(Citation: Kaspersky Equation QA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d661b40-6ebf-470f-a675-142f86b6c649`.
