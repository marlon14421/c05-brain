---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0065"
target_object: "T1059.005"
stix_relationship_id: "relationship--88898d14-9313-4fdd-8ef5-584d8dcdec17"
---
# Relationship 6092: G0065 — uses → T1059.005

**Source object:** [[01 ATT&CK/G0065 - Leviathan|G0065: Leviathan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) has used VBScript.(Citation: Proofpoint Leviathan Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88898d14-9313-4fdd-8ef5-584d8dcdec17`.
