---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0402"
target_object: "T1564.009"
stix_relationship_id: "relationship--950fca51-66e4-43c6-9af0-839e962b8409"
---
# Relationship 6893: S0402 — uses → T1564.009

**Source object:** [[01 ATT&CK/S0402 - OSX-Shlayer|S0402: OSX/Shlayer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.009 - Resource Forking|T1564.009: Resource Forking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX/Shlayer](https://attack.mitre.org/software/S0402) has used a resource fork to hide a compressed binary file of itself from the terminal, Finder, and potentially evade traditional scanners.(Citation: tau bundlore erika noerenberg 2020)(Citation: sentinellabs resource named fork 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--950fca51-66e4-43c6-9af0-839e962b8409`.
