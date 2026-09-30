---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0593"
target_object: "T1113"
stix_relationship_id: "relationship--8852f9e4-c2f1-4d24-8bc6-8539ec4180a5"
---
# Relationship 5313: S0593 — uses → T1113

**Source object:** [[01 ATT&CK/S0593 - ECCENTRICBANDWAGON|S0593: ECCENTRICBANDWAGON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ECCENTRICBANDWAGON](https://attack.mitre.org/software/S0593) can capture screenshots and store them locally.(Citation: CISA EB Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8852f9e4-c2f1-4d24-8bc6-8539ec4180a5`.
