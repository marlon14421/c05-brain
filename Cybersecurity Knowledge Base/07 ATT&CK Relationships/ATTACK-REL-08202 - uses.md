---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1553.006"
stix_relationship_id: "relationship--2856e2ad-4fcd-483a-85bb-99fe8304ee8d"
---
# Relationship 8202: S0089 — uses → T1553.006

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.006 - Code Signing Policy Modification|T1553.006: Code Signing Policy Modification]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackEnergy](https://attack.mitre.org/software/S0089) has enabled the TESTSIGNING boot configuration option to facilitate loading of a driver component.(Citation: F-Secure BlackEnergy 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2856e2ad-4fcd-483a-85bb-99fe8304ee8d`.
