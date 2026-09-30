---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0472"
target_object: "T1071.001"
stix_relationship_id: "relationship--bea01073-649a-4b27-a9f5-72533faae8cc"
---
# Relationship 6346: S0472 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0472 - down_new|S0472: down_new]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[down_new](https://attack.mitre.org/software/S0472) has the ability to use HTTP in C2 communications.(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bea01073-649a-4b27-a9f5-72533faae8cc`.
