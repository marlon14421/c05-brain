---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0208"
target_object: "T1005"
stix_relationship_id: "relationship--e7126875-bb0f-48d0-845f-6b8951ce8507"
---
# Relationship 9718: S0208 — uses → T1005

**Source object:** [[01 ATT&CK/S0208 - Pasam|S0208: Pasam]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pasam](https://attack.mitre.org/software/S0208) creates a backdoor through which remote attackers can retrieve files.(Citation: Symantec Pasam May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7126875-bb0f-48d0-845f-6b8951ce8507`.
