---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0354"
target_object: "T1082"
stix_relationship_id: "relationship--2910f5f5-38d6-418a-8566-23d31b93b124"
---
# Relationship 5768: S0354 — uses → T1082

**Source object:** [[01 ATT&CK/S0354 - Denis|S0354: Denis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Denis](https://attack.mitre.org/software/S0354) collects OS information and the computer name from the victim’s machine.(Citation: Securelist Denis April 2017)(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2910f5f5-38d6-418a-8566-23d31b93b124`.
