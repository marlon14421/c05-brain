---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0575"
target_object: "T1018"
stix_relationship_id: "relationship--9c424acf-2a41-4b34-867f-590ade731fc2"
---
# Relationship 8546: S0575 — uses → T1018

**Source object:** [[01 ATT&CK/S0575 - Conti|S0575: Conti]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Conti](https://attack.mitre.org/software/S0575) has the ability to discover hosts on a target network.(Citation: CrowdStrike Wizard Spider October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c424acf-2a41-4b34-867f-590ade731fc2`.
