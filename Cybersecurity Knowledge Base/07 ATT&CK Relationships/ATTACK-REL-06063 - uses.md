---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0006"
target_object: "S0057"
stix_relationship_id: "relationship--abb6d14e-e76f-4437-8006-1a084ecd5e1b"
---
# Relationship 6063: C0006 — uses → S0057

**Source object:** [[01 ATT&CK/C0006 - Operation Honeybee|C0006: Operation Honeybee]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0057 - Tasklist|S0057: Tasklist]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: McAfee Honeybee)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--abb6d14e-e76f-4437-8006-1a084ecd5e1b`.
