---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0354"
target_object: "T1016"
stix_relationship_id: "relationship--4cc3f3af-73f1-4f36-9e28-de4f8ecc3247"
---
# Relationship 8439: S0354 — uses → T1016

**Source object:** [[01 ATT&CK/S0354 - Denis|S0354: Denis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Denis](https://attack.mitre.org/software/S0354) uses ipconfig to gather the IP address from the system.(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4cc3f3af-73f1-4f36-9e28-de4f8ecc3247`.
