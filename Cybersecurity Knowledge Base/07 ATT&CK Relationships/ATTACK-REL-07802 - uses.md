---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0396"
target_object: "T1203"
stix_relationship_id: "relationship--66cadf3d-bfb7-4b75-a659-06b3cb1bbd37"
---
# Relationship 7802: S0396 — uses → T1203

**Source object:** [[01 ATT&CK/S0396 - EvilBunny|S0396: EvilBunny]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EvilBunny](https://attack.mitre.org/software/S0396) has exploited CVE-2011-4369, a vulnerability in the PRC component in Adobe Reader.(Citation: Cyphort EvilBunny Dec 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66cadf3d-bfb7-4b75-a659-06b3cb1bbd37`.
