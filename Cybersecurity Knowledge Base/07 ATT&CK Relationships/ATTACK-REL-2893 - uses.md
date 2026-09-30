---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0081"
target_object: "T1218.011"
stix_relationship_id: "relationship--37ab6b56-033c-4cb6-8d1b-e7ff5dcf668d"
---
# Relationship 2893: S0081 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0081 - Elise|S0081: Elise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

After copying itself to a DLL file, a variant of [Elise](https://attack.mitre.org/software/S0081) calls the DLL file using rundll32.exe.(Citation: Lotus Blossom Jun 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--37ab6b56-033c-4cb6-8d1b-e7ff5dcf668d`.
