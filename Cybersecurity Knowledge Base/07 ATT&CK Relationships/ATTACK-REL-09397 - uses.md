---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1021.006"
stix_relationship_id: "relationship--f947ae1c-1042-469d-b00e-84784e406cec"
---
# Relationship 9397: G0102 — uses → T1021.006

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.006 - Windows Remote Management|T1021.006: Windows Remote Management]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used Window Remote Management to move laterally through a victim network.(Citation: DHS/CISA Ransomware Targeting Healthcare October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f947ae1c-1042-469d-b00e-84784e406cec`.
