---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0112"
target_object: "T1204.002"
stix_relationship_id: "relationship--f7800d2b-7eb5-4efe-ac8d-503c187d18ef"
---
# Relationship 9038: G0112 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0112 - Windshift|G0112: Windshift]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Windshift](https://attack.mitre.org/groups/G0112) has used e-mail attachments to lure victims into executing malicious code.(Citation: SANS Windshift August 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7800d2b-7eb5-4efe-ac8d-503c187d18ef`.
