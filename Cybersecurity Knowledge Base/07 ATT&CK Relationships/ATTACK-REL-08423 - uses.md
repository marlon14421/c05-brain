---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0333"
target_object: "T1057"
stix_relationship_id: "relationship--e29fa4df-f835-48e1-a83b-279818993793"
---
# Relationship 8423: S0333 — uses → T1057

**Source object:** [[01 ATT&CK/S0333 - UBoatRAT|S0333: UBoatRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UBoatRAT](https://attack.mitre.org/software/S0333) can list running processes on the system.(Citation: PaloAlto UBoatRAT Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e29fa4df-f835-48e1-a83b-279818993793`.
