---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0018"
target_object: "T1056.001"
stix_relationship_id: "relationship--7a30e6e7-ed64-47b1-b368-c1cec96d5fbf"
---
# Relationship 9225: S0018 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0018 - Sykipot|S0018: Sykipot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sykipot](https://attack.mitre.org/software/S0018) contains keylogging functionality to steal passwords.(Citation: Alienvault Sykipot DOD Smart Cards)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a30e6e7-ed64-47b1-b368-c1cec96d5fbf`.
