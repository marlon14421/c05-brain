---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0693"
target_object: "T1485"
stix_relationship_id: "relationship--a65cc371-4fa4-48e9-b95d-22ac81d67085"
---
# Relationship 5801: S0693 — uses → T1485

**Source object:** [[01 ATT&CK/S0693 - CaddyWiper|S0693: CaddyWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CaddyWiper](https://attack.mitre.org/software/S0693) can work alphabetically through drives on a compromised system to take ownership of and overwrite all files.(Citation: ESET CaddyWiper March 2022)(Citation: Cisco CaddyWiper March 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a65cc371-4fa4-48e9-b95d-22ac81d67085`.
