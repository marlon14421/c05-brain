---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0077"
target_object: "S0413"
stix_relationship_id: "relationship--a55d75ab-f5bb-4892-80de-c878be26a67d"
---
# Relationship 7685: G0077 — uses → S0413

**Source object:** [[01 ATT&CK/G0077 - Leafminer|G0077: Leafminer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0413 - MailSniper|S0413: MailSniper]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Symantec Leafminer July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a55d75ab-f5bb-4892-80de-c878be26a67d`.
