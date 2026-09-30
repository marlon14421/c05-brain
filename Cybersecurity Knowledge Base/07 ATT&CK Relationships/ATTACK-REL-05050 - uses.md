---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1017"
target_object: "T1555.003"
stix_relationship_id: "relationship--b620d7cd-34ef-402c-b8c2-e36c27162c63"
---
# Relationship 5050: G1017 — uses → T1555.003

**Source object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) has targeted network administrator browser data including browsing history and stored credentials.(Citation: CISA AA24-038A PRC Critical Infrastructure February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b620d7cd-34ef-402c-b8c2-e36c27162c63`.
