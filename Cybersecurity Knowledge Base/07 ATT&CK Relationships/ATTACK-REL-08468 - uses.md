---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0252"
target_object: "T1083"
stix_relationship_id: "relationship--69127424-40bb-4b92-8558-6fe1561e0a59"
---
# Relationship 8468: S0252 — uses → T1083

**Source object:** [[01 ATT&CK/S0252 - Brave Prince|S0252: Brave Prince]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Brave Prince](https://attack.mitre.org/software/S0252) gathers file and directory information from the victim’s machine.(Citation: McAfee Gold Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69127424-40bb-4b92-8558-6fe1561e0a59`.
