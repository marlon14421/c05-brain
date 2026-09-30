---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0165"
target_object: "T1018"
stix_relationship_id: "relationship--8765dd7e-33cc-4040-927d-bf0aa16d3d79"
---
# Relationship 9725: S0165 — uses → T1018

**Source object:** [[01 ATT&CK/S0165 - OSInfo|S0165: OSInfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSInfo](https://attack.mitre.org/software/S0165) performs a connection test to discover remote systems in the network(Citation: Symantec Buckeye)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8765dd7e-33cc-4040-927d-bf0aa16d3d79`.
