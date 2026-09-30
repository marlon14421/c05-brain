---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0561"
target_object: "T1497.003"
stix_relationship_id: "relationship--d231c64f-4a5f-43b8-a6e8-6ddd74d14eb3"
---
# Relationship 2650: S0561 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0561 - GuLoader|S0561: GuLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GuLoader](https://attack.mitre.org/software/S0561) has the ability to perform anti-debugging based on time checks, API calls, and CPUID.(Citation: Medium Eli Salem GuLoader April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d231c64f-4a5f-43b8-a6e8-6ddd74d14eb3`.
