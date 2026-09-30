---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0001"
target_object: "T1053.005"
stix_relationship_id: "relationship--3cfb23f1-ae6c-4ba9-acf0-b5e592ea5597"
---
# Relationship 3214: C0001 — uses → T1053.005

**Source object:** [[01 ATT&CK/C0001 - Frankenstein|C0001: Frankenstein]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Frankenstein](https://attack.mitre.org/campaigns/C0001), the threat actors established persistence through a scheduled task using the command: `/Create /F /SC DAILY /ST 09:00 /TN WinUpdate /TR`, named "WinUpdate" (Citation: Talos Frankenstein June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3cfb23f1-ae6c-4ba9-acf0-b5e592ea5597`.
