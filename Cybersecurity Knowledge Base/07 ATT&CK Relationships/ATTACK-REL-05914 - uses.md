---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1090.002"
stix_relationship_id: "relationship--a8085af7-fcbb-4c1d-8eef-0ae509dac516"
---
# Relationship 5914: G0016 — uses → T1090.002

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) uses compromised residential endpoints as proxies for defense evasion and network access.(Citation: NCSC et al APT29 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8085af7-fcbb-4c1d-8eef-0ae509dac516`.
