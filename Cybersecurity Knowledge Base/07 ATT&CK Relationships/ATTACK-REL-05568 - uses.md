---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0091"
target_object: "S0191"
stix_relationship_id: "relationship--465385c3-8659-4225-82b3-215dfc66ba83"
---
# Relationship 5568: G0091 — uses → S0191

**Source object:** [[01 ATT&CK/G0091 - Silence|G0091: Silence]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0191 - Winexe|S0191: Winexe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: SecureList Silence Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--465385c3-8659-4225-82b3-215dfc66ba83`.
