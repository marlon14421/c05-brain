---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0026"
target_object: "T1105"
stix_relationship_id: "relationship--a8fd0806-56eb-4438-bcce-18f7851a07c6"
---
# Relationship 9082: C0026 — uses → T1105

**Source object:** [[01 ATT&CK/C0026 - C0026|C0026: C0026]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0026](https://attack.mitre.org/campaigns/C0026), the threat actors downloaded malicious payloads onto select compromised hosts.(Citation: Mandiant Suspected Turla Campaign February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8fd0806-56eb-4438-bcce-18f7851a07c6`.
