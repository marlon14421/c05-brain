---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "T1027.006"
stix_relationship_id: "relationship--5bc4476e-9693-424c-b4d1-fd3a9ca996f3"
---
# Relationship 6678: G0016 — uses → T1027.006

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.006 - HTML Smuggling|T1027.006: HTML Smuggling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT29](https://attack.mitre.org/groups/G0016) has embedded an ISO file within an HTML attachment that contained JavaScript code to initiate malware execution.(Citation: ESET T3 Threat Report 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5bc4476e-9693-424c-b4d1-fd3a9ca996f3`.
