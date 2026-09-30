---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0584"
target_object: "T1569.001"
stix_relationship_id: "relationship--3eb174df-6b12-484e-89c1-fce208e6cdfd"
---
# Relationship 7798: S0584 — uses → T1569.001

**Source object:** [[01 ATT&CK/S0584 - AppleJeus|S0584: AppleJeus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.001 - Launchctl|T1569.001: Launchctl]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AppleJeus](https://attack.mitre.org/software/S0584) has loaded a plist file using the launchctl command.(Citation: CISA AppleJeus Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3eb174df-6b12-484e-89c1-fce208e6cdfd`.
