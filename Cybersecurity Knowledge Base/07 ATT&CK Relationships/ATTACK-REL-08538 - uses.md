---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0526"
target_object: "T1056.001"
stix_relationship_id: "relationship--e7e2eed9-ef15-4b6b-890b-72d2b47ca685"
---
# Relationship 8538: S0526 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0526 - KGH_SPY|S0526: KGH_SPY]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KGH_SPY](https://attack.mitre.org/software/S0526) can perform keylogging by polling the GetAsyncKeyState() function.(Citation: Cybereason Kimsuky November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7e2eed9-ef15-4b6b-890b-72d2b47ca685`.
