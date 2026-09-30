---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0695"
target_object: "T1071.001"
stix_relationship_id: "relationship--717079c0-7f34-42f6-927f-9ee321447c13"
---
# Relationship 9599: S0695 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0695 - Donut|S0695: Donut]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Donut](https://attack.mitre.org/software/S0695) can use HTTP to download previously staged shellcode payloads.(Citation: Donut Github)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--717079c0-7f34-42f6-927f-9ee321447c13`.
