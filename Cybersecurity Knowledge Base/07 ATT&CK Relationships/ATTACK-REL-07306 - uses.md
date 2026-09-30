---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1110.003"
stix_relationship_id: "relationship--6c4b2975-6cad-4a10-8006-1e2e973a8a8b"
---
# Relationship 7306: G0016 — uses → T1110.003

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.003 - Password Spraying|T1110.003: Password Spraying]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has conducted brute force password spray attacks.(Citation: MSRC Nobelium June 2021)(Citation: MSTIC Nobelium Oct 2021)(Citation: NCSC et al APT29 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c4b2975-6cad-4a10-8006-1e2e973a8a8b`.
