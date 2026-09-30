---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0138"
target_object: "T1105"
stix_relationship_id: "relationship--ef8385b2-e62c-4854-9a0b-f23d6de334cd"
---
# Relationship 9768: G0138 — uses → T1105

**Source object:** [[01 ATT&CK/G0138 - Andariel|G0138: Andariel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Andariel](https://attack.mitre.org/groups/G0138) has downloaded additional tools and malware onto compromised hosts.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef8385b2-e62c-4854-9a0b-f23d6de334cd`.
