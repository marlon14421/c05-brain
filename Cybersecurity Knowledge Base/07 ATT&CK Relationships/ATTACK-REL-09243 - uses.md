---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0516"
target_object: "T1071.001"
stix_relationship_id: "relationship--4b9cbe06-8c1f-4596-ad87-fa19e60e8ec3"
---
# Relationship 9243: S0516 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0516 - SoreFang|S0516: SoreFang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SoreFang](https://attack.mitre.org/software/S0516) can use HTTP in C2 communications.(Citation: CISA SoreFang July 2016)(Citation: NCSC APT29 July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b9cbe06-8c1f-4596-ad87-fa19e60e8ec3`.
