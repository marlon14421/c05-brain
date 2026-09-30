---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0454"
target_object: "T1010"
stix_relationship_id: "relationship--13e89239-af0e-4f3c-9bb9-42b113f64873"
---
# Relationship 4030: S0454 — uses → T1010

**Source object:** [[01 ATT&CK/S0454 - Cadelspy|S0454: Cadelspy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cadelspy](https://attack.mitre.org/software/S0454) has the ability to identify open windows on the compromised host.(Citation: Symantec Chafer Dec 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13e89239-af0e-4f3c-9bb9-42b113f64873`.
