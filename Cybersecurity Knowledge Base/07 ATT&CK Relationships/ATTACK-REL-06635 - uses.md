---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0234"
target_object: "T1005"
stix_relationship_id: "relationship--f5f24a8f-6d98-4f00-9db2-e92189f7d67a"
---
# Relationship 6635: S0234 — uses → T1005

**Source object:** [[01 ATT&CK/S0234 - Bandook|S0234: Bandook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bandook](https://attack.mitre.org/software/S0234) can collect local files from the system .(Citation: CheckPoint Bandook Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5f24a8f-6d98-4f00-9db2-e92189f7d67a`.
