---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0695"
target_object: "T1059.006"
stix_relationship_id: "relationship--15b1bc2a-4cd1-4b82-90b0-2aa6e69637c7"
---
# Relationship 7373: S0695 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0695 - Donut|S0695: Donut]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Donut](https://attack.mitre.org/software/S0695) can generate shellcode outputs that execute via Python.(Citation: Donut Github)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--15b1bc2a-4cd1-4b82-90b0-2aa6e69637c7`.
