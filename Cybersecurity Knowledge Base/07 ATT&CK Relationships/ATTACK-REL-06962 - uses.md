---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0081"
target_object: "T1105"
stix_relationship_id: "relationship--0f47a6e7-af7e-4e23-a401-4dec08da4e64"
---
# Relationship 6962: G0081 — uses → T1105

**Source object:** [[01 ATT&CK/G0081 - Tropic Trooper|G0081: Tropic Trooper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tropic Trooper](https://attack.mitre.org/groups/G0081) has used a delivered trojan to download additional files.(Citation: TrendMicro Tropic Trooper May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f47a6e7-af7e-4e23-a401-4dec08da4e64`.
