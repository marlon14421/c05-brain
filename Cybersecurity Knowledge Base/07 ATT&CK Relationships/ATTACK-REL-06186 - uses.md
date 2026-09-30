---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0147"
target_object: "T1218.011"
stix_relationship_id: "relationship--a20b8e4c-330f-4e91-b4f6-e58e5800d690"
---
# Relationship 6186: S0147 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0147 - Pteranodon|S0147: Pteranodon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Pteranodon](https://attack.mitre.org/software/S0147) executes functions using rundll32.exe.(Citation: Palo Alto Gamaredon Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a20b8e4c-330f-4e91-b4f6-e58e5800d690`.
