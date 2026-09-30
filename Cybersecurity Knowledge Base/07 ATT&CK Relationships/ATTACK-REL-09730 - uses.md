---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0051"
target_object: "T1078"
stix_relationship_id: "relationship--d3b787ec-795c-481b-94e5-ff42dc56d79d"
---
# Relationship 9730: G0051 — uses → T1078

**Source object:** [[01 ATT&CK/G0051 - FIN10|G0051: FIN10]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN10](https://attack.mitre.org/groups/G0051) has used stolen credentials to connect remotely to victim networks using VPNs protected with only a single factor.(Citation: FireEye FIN10 June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3b787ec-795c-481b-94e5-ff42dc56d79d`.
