---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0402"
target_object: "T1176.001"
stix_relationship_id: "relationship--5b5b5650-916b-4519-8cbd-da90589fe7b6"
---
# Relationship 7274: S0402 — uses → T1176.001

**Source object:** [[01 ATT&CK/S0402 - OSX-Shlayer|S0402: OSX/Shlayer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1176.001 - Browser Extensions|T1176.001: Browser Extensions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OSX/Shlayer](https://attack.mitre.org/software/S0402) can install malicious Safari browser extensions to serve ads.(Citation: Intego Shlayer Apr 2018)(Citation: Malwarebytes Crossrider Apr 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b5b5650-916b-4519-8cbd-da90589fe7b6`.
