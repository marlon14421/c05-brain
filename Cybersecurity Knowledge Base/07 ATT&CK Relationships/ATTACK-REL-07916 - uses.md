---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0105"
target_object: "T1040"
stix_relationship_id: "relationship--c2ba1f7a-1951-47df-855b-3f42a60a9901"
---
# Relationship 7916: G0105 — uses → T1040

**Source object:** [[01 ATT&CK/G0105 - DarkVishnya|G0105: DarkVishnya]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkVishnya](https://attack.mitre.org/groups/G0105) used network sniffing to obtain login data. (Citation: Securelist DarkVishnya Dec 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2ba1f7a-1951-47df-855b-3f42a60a9901`.
