---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0678"
target_object: "T1027.013"
stix_relationship_id: "relationship--00f44cd5-9afc-472f-9743-251d243798a0"
---
# Relationship 5388: S0678 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0678 - Torisma|S0678: Torisma]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Torisma](https://attack.mitre.org/software/S0678) has been Base64 encoded and AES encrypted.(Citation: McAfee Lazarus Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00f44cd5-9afc-472f-9743-251d243798a0`.
