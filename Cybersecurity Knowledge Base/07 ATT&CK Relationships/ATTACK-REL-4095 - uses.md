---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1034"
target_object: "S0190"
stix_relationship_id: "relationship--2140f26b-a8ec-4a7e-9903-7df7ea5a1abb"
---
# Relationship 4095: G1034 — uses → S0190

**Source object:** [[01 ATT&CK/G1034 - Daggerfly|G1034: Daggerfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0190 - BITSAdmin|S0190: BITSAdmin]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Daggerfly](https://attack.mitre.org/groups/G1034) has used [BITSAdmin](https://attack.mitre.org/software/S0190) to retrieve files from remote locations to run on victim systems.(Citation: Symantec Daggerfly 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2140f26b-a8ec-4a7e-9903-7df7ea5a1abb`.
