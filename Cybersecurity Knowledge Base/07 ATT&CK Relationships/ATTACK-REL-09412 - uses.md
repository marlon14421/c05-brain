---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0680"
target_object: "T1071.001"
stix_relationship_id: "relationship--9d8ea8fe-c0d5-4f3b-b0ed-253708c07a0b"
---
# Relationship 9412: S0680 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0680 - LitePower|S0680: LitePower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LitePower](https://attack.mitre.org/software/S0680) can use HTTP and HTTPS for C2 communications.(Citation: Kaspersky WIRTE November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d8ea8fe-c0d5-4f3b-b0ed-253708c07a0b`.
