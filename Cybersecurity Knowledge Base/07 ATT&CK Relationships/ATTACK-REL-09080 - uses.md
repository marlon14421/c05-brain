---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0402"
target_object: "T1036.005"
stix_relationship_id: "relationship--8f8d2b41-acb9-4fdf-ad90-c59fd6fad882"
---
# Relationship 9080: S0402 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0402 - OSX-Shlayer|S0402: OSX/Shlayer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX/Shlayer](https://attack.mitre.org/software/S0402) can masquerade as a Flash Player update.(Citation: Carbon Black Shlayer Feb 2019)(Citation: Intego Shlayer Feb 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f8d2b41-acb9-4fdf-ad90-c59fd6fad882`.
