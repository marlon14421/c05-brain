---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0530"
target_object: "T1115"
stix_relationship_id: "relationship--ce8220fc-98ee-4b48-b98c-8be15a429410"
---
# Relationship 5119: S0530 — uses → T1115

**Source object:** [[01 ATT&CK/S0530 - Melcoz|S0530: Melcoz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Melcoz](https://attack.mitre.org/software/S0530) can monitor content saved to the clipboard.(Citation: Securelist Brazilian Banking Malware July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce8220fc-98ee-4b48-b98c-8be15a429410`.
