---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1056.001"
stix_relationship_id: "relationship--a5c8b6af-8685-4068-8046-122bbd5f8845"
---
# Relationship 7464: S0409 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/software/S0409) logs keystrokes from the victim’s machine.(Citation: ESET Machete July 2019)(Citation: Securelist Machete Aug 2014)(Citation: Cylance Machete Mar 2017)(Citation: 360 Machete Sep 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a5c8b6af-8685-4068-8046-122bbd5f8845`.
