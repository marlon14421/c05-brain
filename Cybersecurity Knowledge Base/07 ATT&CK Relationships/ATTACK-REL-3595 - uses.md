---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0021"
target_object: "T1218.011"
stix_relationship_id: "relationship--0e8a4965-f609-4cf1-bded-2b4a1ef5c5f3"
---
# Relationship 3595: C0021 — uses → T1218.011

**Source object:** [[01 ATT&CK/C0021 - C0021|C0021: C0021]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0021](https://attack.mitre.org/campaigns/C0021), the threat actors used `rundll32.exe` to execute the [Cobalt Strike](https://attack.mitre.org/software/S0154) Beacon loader DLL.(Citation: FireEye APT29 Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e8a4965-f609-4cf1-bded-2b4a1ef5c5f3`.
