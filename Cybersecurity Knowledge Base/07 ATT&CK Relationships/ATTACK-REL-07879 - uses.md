---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0090"
target_object: "T1684.001"
stix_relationship_id: "relationship--c3827f83-e909-4911-87ca-af039b369480"
---
# Relationship 7879: G0090 — uses → T1684.001

**Source object:** [[01 ATT&CK/G0090 - WIRTE|G0090: WIRTE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1684.001 - Impersonation|T1684.001: Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WIRTE](https://attack.mitre.org/groups/G0090) has used utilized look-alike domains and graphics of trusted security solution providers to entice victims to click on phishing links.(Citation: Check Point Wirte NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c3827f83-e909-4911-87ca-af039b369480`.
