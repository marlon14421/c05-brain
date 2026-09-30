---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0226"
target_object: "T1059.005"
stix_relationship_id: "relationship--4287de65-be1d-44aa-9c50-9c391e321597"
---
# Relationship 4831: S0226 — uses → T1059.005

**Source object:** [[01 ATT&CK/S0226 - Smoke Loader|S0226: Smoke Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Smoke Loader](https://attack.mitre.org/software/S0226) adds a Visual Basic script in the Startup folder to deploy the payload.(Citation: Malwarebytes SmokeLoader 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4287de65-be1d-44aa-9c50-9c391e321597`.
