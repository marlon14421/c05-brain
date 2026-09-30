---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1555.003"
stix_relationship_id: "relationship--29403801-cdba-4de9-9b9c-c1295b9eccf6"
---
# Relationship 5949: S0356 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KONNI](https://attack.mitre.org/software/S0356) can steal profiles (containing credential information) from Firefox, Chrome, and Opera.(Citation: Talos Konni May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29403801-cdba-4de9-9b9c-c1295b9eccf6`.
