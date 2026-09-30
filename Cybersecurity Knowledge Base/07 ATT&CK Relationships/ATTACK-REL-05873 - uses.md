---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0342"
target_object: "T1553.002"
stix_relationship_id: "relationship--496017cd-f22a-4295-931c-70bb672985f8"
---
# Relationship 5873: S0342 — uses → T1553.002

**Source object:** [[01 ATT&CK/S0342 - GreyEnergy|S0342: GreyEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GreyEnergy](https://attack.mitre.org/software/S0342) digitally signs the malware with a code-signing certificate.(Citation: ESET GreyEnergy Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--496017cd-f22a-4295-931c-70bb672985f8`.
