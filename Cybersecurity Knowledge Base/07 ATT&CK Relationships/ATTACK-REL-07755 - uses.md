---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9013"
target_object: "T1556.004"
stix_relationship_id: "relationship--fb6cf7ca-c649-4ca9-95aa-577cf9018c19"
---
# Relationship 7755: S9013 — uses → T1556.004

**Source object:** [[01 ATT&CK/S9013 - DRYHOOK|S9013: DRYHOOK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556.004 - Network Device Authentication|T1556.004: Network Device Authentication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DRYHOOK](https://attack.mitre.org/software/S9013) has patched victim appliances authentication routines to capture credentials in plaintext as users log in.(Citation: Google UNC5221 Ivanti January 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb6cf7ca-c649-4ca9-95aa-577cf9018c19`.
