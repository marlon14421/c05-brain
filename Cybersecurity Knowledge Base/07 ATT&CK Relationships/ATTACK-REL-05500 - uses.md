---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "T1016.001"
stix_relationship_id: "relationship--86c55cd3-efb5-4bd3-9958-a5af1f1b0679"
---
# Relationship 5500: G1018 — uses → T1016.001

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016.001 - Internet Connection Discovery|T1016.001: Internet Connection Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA2541](https://attack.mitre.org/groups/G1018) has run scripts to check internet connectivity from compromised hosts. (Citation: Cisco Operation Layover September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86c55cd3-efb5-4bd3-9958-a5af1f1b0679`.
