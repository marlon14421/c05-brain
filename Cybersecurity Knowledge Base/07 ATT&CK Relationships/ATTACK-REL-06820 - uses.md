---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0024"
target_object: "T1053.005"
stix_relationship_id: "relationship--57828888-a833-44c7-af2c-e250d799a9bc"
---
# Relationship 6820: S0024 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0024 - Dyre|S0024: Dyre]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dyre](https://attack.mitre.org/software/S0024) has the ability to achieve persistence by adding a new task in the task scheduler to run every minute.(Citation: Malwarebytes Dyreza November 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--57828888-a833-44c7-af2c-e250d799a9bc`.
