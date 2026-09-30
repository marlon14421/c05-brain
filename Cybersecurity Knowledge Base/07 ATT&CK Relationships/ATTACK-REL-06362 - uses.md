---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0493"
target_object: "T1543.003"
stix_relationship_id: "relationship--0fee7bbd-8d36-48e2-b800-9d2f02c06123"
---
# Relationship 6362: S0493 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0493 - GoldenSpy|S0493: GoldenSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GoldenSpy](https://attack.mitre.org/software/S0493) has established persistence by running in the background as an autostart service.(Citation: Trustwave GoldenSpy June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0fee7bbd-8d36-48e2-b800-9d2f02c06123`.
