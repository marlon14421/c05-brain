---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1105"
stix_relationship_id: "relationship--2011a4ee-6b40-45a1-8bcf-f19568d16d02"
---
# Relationship 7940: G0094 — uses → T1105

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has downloaded additional scripts, tools, and malware onto victim systems.(Citation: Talos Kimsuky Nov 2021)(Citation: Crowdstrike GTR2020 Mar 2020)(Citation: Securonix Kimsuky February 2025)(Citation: Aryaka Kimsuky July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2011a4ee-6b40-45a1-8bcf-f19568d16d02`.
