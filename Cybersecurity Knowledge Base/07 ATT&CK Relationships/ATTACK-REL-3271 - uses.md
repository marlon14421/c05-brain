---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0629"
target_object: "T1053.005"
stix_relationship_id: "relationship--afea5bf8-f6e0-4b93-8de6-da2e0cd6f569"
---
# Relationship 3271: S0629 — uses → T1053.005

**Source object:** [[01 ATT&CK/S0629 - RainyDay|S0629: RainyDay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RainyDay](https://attack.mitre.org/software/S0629) can use scheduled tasks to achieve persistence.(Citation: Bitdefender Naikon April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afea5bf8-f6e0-4b93-8de6-da2e0cd6f569`.
