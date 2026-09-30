---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0381"
target_object: "T1082"
stix_relationship_id: "relationship--0d95b411-1192-42d0-96b1-98fe18742a04"
---
# Relationship 8028: S0381 — uses → T1082

**Source object:** [[01 ATT&CK/S0381 - FlawedAmmyy|S0381: FlawedAmmyy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FlawedAmmyy](https://attack.mitre.org/software/S0381) can collect the victim's operating system and computer name during the initial infection.(Citation: Proofpoint TA505 Mar 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d95b411-1192-42d0-96b1-98fe18742a04`.
