---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "S0154"
stix_relationship_id: "relationship--9c61749d-ad78-476d-8cd6-ba4eafc8f74e"
---
# Relationship 8250: G0046 — uses → S0154

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: CrowdStrike Carbon Spider August 2021)(Citation: FBI Flash FIN7 USB)(Citation: Mandiant FIN7 Apr 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c61749d-ad78-476d-8cd6-ba4eafc8f74e`.
