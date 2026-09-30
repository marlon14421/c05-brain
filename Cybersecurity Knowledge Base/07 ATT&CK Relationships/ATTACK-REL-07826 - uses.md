---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1099"
target_object: "T1090"
stix_relationship_id: "relationship--d8e8d071-fa60-4b6d-a0a4-dc6102f229c8"
---
# Relationship 7826: S1099 — uses → T1090

**Source object:** [[01 ATT&CK/S1099 - Samurai|S1099: Samurai]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Samurai](https://attack.mitre.org/software/S1099) has the ability to proxy connections to specified remote IPs and ports through a a proxy module.(Citation: Kaspersky ToddyCat June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d8e8d071-fa60-4b6d-a0a4-dc6102f229c8`.
