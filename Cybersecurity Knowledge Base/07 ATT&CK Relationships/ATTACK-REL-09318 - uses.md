---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0652"
target_object: "T1518.001"
stix_relationship_id: "relationship--6afb86e4-cb3b-40f5-ab03-10db5e0e9302"
---
# Relationship 9318: S0652 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0652 - MarkiRAT|S0652: MarkiRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MarkiRAT](https://attack.mitre.org/software/S0652) can check for running processes on the victim’s machine to look for Kaspersky and Bitdefender antivirus products.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6afb86e4-cb3b-40f5-ab03-10db5e0e9302`.
