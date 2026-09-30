---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0020"
target_object: "T1071.001"
stix_relationship_id: "relationship--27561720-48cb-427c-892f-b31ce4d61d9e"
---
# Relationship 8437: S0020 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0020 - China Chopper|S0020: China Chopper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[China Chopper](https://attack.mitre.org/software/S0020)'s server component executes code sent via HTTP POST commands.(Citation: FireEye Periscope March 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27561720-48cb-427c-892f-b31ce4d61d9e`.
