---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0205"
target_object: "T1082"
stix_relationship_id: "relationship--70e81cc7-9dd6-4349-b7ab-212a46591cff"
---
# Relationship 5807: S0205 — uses → T1082

**Source object:** [[01 ATT&CK/S0205 - Naid|S0205: Naid]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Naid](https://attack.mitre.org/software/S0205) collects a unique identifier (UID) from a compromised host.(Citation: Symantec Naid June 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70e81cc7-9dd6-4349-b7ab-212a46591cff`.
