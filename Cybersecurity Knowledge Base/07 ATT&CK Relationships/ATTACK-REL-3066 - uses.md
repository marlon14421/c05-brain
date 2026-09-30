---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1152"
target_object: "T1574.014"
stix_relationship_id: "relationship--bf1c6e17-b555-4886-afd0-b5959b36f38e"
---
# Relationship 3066: S1152 — uses → T1574.014

**Source object:** [[01 ATT&CK/S1152 - IMAPLoader|S1152: IMAPLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.014 - AppDomainManager|T1574.014: AppDomainManager]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IMAPLoader](https://attack.mitre.org/software/S1152) is executed via the AppDomainManager injection technique.(Citation: PWC Yellow Liderc 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf1c6e17-b555-4886-afd0-b5959b36f38e`.
