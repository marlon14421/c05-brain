---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0275"
target_object: "T1678"
stix_relationship_id: "relationship--ed3cec58-c1b7-4222-9b0d-609793f86d1e"
---
# Relationship 9228: S0275 — uses → T1678

**Source object:** [[01 ATT&CK/S0275 - UPPERCUT|S0275: UPPERCUT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1678 - Delay Execution|T1678: Delay Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UPPERCUT](https://attack.mitre.org/software/S0275) can use a sleep function to delay execution.(Citation: Trend Micro Earth Kasha Updates APR 2025)(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed3cec58-c1b7-4222-9b0d-609793f86d1e`.
