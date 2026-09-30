---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1005"
target_object: "T1567.002"
stix_relationship_id: "relationship--3077e0e6-4540-4f0d-a2ec-c4db78a35a0e"
---
# Relationship 8278: G1005 — uses → T1567.002

**Source object:** [[01 ATT&CK/G1005 - POLONIUM|G1005: POLONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[POLONIUM](https://attack.mitre.org/groups/G1005) has exfiltrated stolen data to [POLONIUM](https://attack.mitre.org/groups/G1005)-owned OneDrive and Dropbox accounts.(Citation: Microsoft POLONIUM June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3077e0e6-4540-4f0d-a2ec-c4db78a35a0e`.
