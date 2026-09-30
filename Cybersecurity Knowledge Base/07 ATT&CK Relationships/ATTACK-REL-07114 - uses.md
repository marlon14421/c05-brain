---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1106"
stix_relationship_id: "relationship--cad2a13a-eb81-4c1c-8d16-beac4bf79625"
---
# Relationship 7114: G0082 — uses → T1106

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has used the Windows API to execute code within a victim's system.(Citation: CISA AA20-239A BeagleBoyz August 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cad2a13a-eb81-4c1c-8d16-beac4bf79625`.
