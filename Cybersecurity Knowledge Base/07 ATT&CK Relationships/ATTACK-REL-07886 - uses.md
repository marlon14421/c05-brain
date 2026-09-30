---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0402"
target_object: "T1204.002"
stix_relationship_id: "relationship--557288c3-8463-4900-b2e5-aa9856d428cd"
---
# Relationship 7886: S0402 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0402 - OSX-Shlayer|S0402: OSX/Shlayer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX/Shlayer](https://attack.mitre.org/software/S0402) has relied on users mounting and executing a malicious DMG file.(Citation: Carbon Black Shlayer Feb 2019)(Citation: Intego Shlayer Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--557288c3-8463-4900-b2e5-aa9856d428cd`.
