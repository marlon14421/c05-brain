---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1036"
target_object: "T1550.001"
stix_relationship_id: "relationship--41f072bf-ec21-4a83-bb25-6c84fce8ca5d"
---
# Relationship 0309: M1036 — mitigates → T1550.001

**Source object:** [[01 ATT&CK/M1036 - Account Use Policies|M1036: Account Use Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1550.001 - Application Access Token|T1550.001: Application Access Token]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Where possible, consider restricting the use of access tokens outside of expected contexts. For example, in AWS environments, consider using data perimeters to prevent credential use outside of an expected network.(Citation: AWS Data Perimeters)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41f072bf-ec21-4a83-bb25-6c84fce8ca5d`.
