---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0207"
target_object: "T1090"
stix_relationship_id: "relationship--b150e3fd-54c0-49ec-a41f-860e92712344"
---
# Relationship 7061: S0207 — uses → T1090

**Source object:** [[01 ATT&CK/S0207 - Vasport|S0207: Vasport]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Vasport](https://attack.mitre.org/software/S0207) is capable of tunneling though a proxy.(Citation: Symantec Vasport May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b150e3fd-54c0-49ec-a41f-860e92712344`.
