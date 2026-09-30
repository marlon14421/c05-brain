---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0176"
target_object: "T1068"
stix_relationship_id: "relationship--dbccbeab-26c9-476e-b529-c193f9796cbc"
---
# Relationship 9899: S0176 — uses → T1068

**Source object:** [[01 ATT&CK/S0176 - Wingbird|S0176: Wingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wingbird](https://attack.mitre.org/software/S0176) exploits CVE-2016-4117 to allow an executable to gain escalated privileges.(Citation: Microsoft SIR Vol 21)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbccbeab-26c9-476e-b529-c193f9796cbc`.
