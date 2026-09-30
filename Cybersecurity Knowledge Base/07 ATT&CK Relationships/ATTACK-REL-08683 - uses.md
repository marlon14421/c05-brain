---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0087"
target_object: "T1204.001"
stix_relationship_id: "relationship--77e0980c-de43-48a8-8df3-b924f8d91b51"
---
# Relationship 8683: G0087 — uses → T1204.001

**Source object:** [[01 ATT&CK/G0087 - APT39|G0087: APT39]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.001 - Malicious Link|T1204.001: Malicious Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT39](https://attack.mitre.org/groups/G0087) has sent spearphishing emails in an attempt to lure users to click on a malicious link.(Citation: FireEye APT39 Jan 2019)(Citation: FBI FLASH APT39 September 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77e0980c-de43-48a8-8df3-b924f8d91b51`.
