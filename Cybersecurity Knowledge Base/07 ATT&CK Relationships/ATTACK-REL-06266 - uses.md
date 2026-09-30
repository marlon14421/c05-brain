---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1003"
target_object: "T1588.005"
stix_relationship_id: "relationship--af2fa05b-f278-448e-aa8b-6e24af194484"
---
# Relationship 6266: G1003 — uses → T1588.005

**Source object:** [[01 ATT&CK/G1003 - Ember Bear|G1003: Ember Bear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.005 - Exploits|T1588.005: Exploits]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ember Bear](https://attack.mitre.org/groups/G1003) has obtained exploitation scripts against publicly-disclosed vulnerabilities from public repositories.(Citation: CISA GRU29155 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af2fa05b-f278-448e-aa8b-6e24af194484`.
