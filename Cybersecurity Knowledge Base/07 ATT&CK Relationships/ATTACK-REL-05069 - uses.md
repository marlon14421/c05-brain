---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1018"
target_object: "T1588.001"
stix_relationship_id: "relationship--3c2faef1-3fa6-4942-be18-460a8e6ec815"
---
# Relationship 5069: G1018 — uses → T1588.001

**Source object:** [[01 ATT&CK/G1018 - TA2541|G1018: TA2541]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.001 - Malware|T1588.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TA2541](https://attack.mitre.org/groups/G1018) has used multiple strains of malware available for purchase on criminal forums or in open-source repositories.(Citation: Proofpoint TA2541 February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3c2faef1-3fa6-4942-be18-460a8e6ec815`.
