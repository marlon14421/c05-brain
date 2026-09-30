---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0126"
target_object: "T1090.001"
stix_relationship_id: "relationship--49a11d2f-7945-4603-b409-d66420b94533"
---
# Relationship 8194: G0126 — uses → T1090.001

**Source object:** [[01 ATT&CK/G0126 - Higaisa|G0126: Higaisa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.001 - Internal Proxy|T1090.001: Internal Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Higaisa](https://attack.mitre.org/groups/G0126) discovered system proxy settings and used them if available.(Citation: Zscaler Higaisa 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49a11d2f-7945-4603-b409-d66420b94533`.
