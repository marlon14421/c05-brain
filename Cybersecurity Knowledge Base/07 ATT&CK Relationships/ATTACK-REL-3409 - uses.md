---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0143"
target_object: "T1218.011"
stix_relationship_id: "relationship--de6db2bf-4ccf-4103-83a5-424ca960fede"
---
# Relationship 3409: G0143 — uses → T1218.011

**Source object:** [[01 ATT&CK/G0143 - Aquatic Panda|G0143: Aquatic Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Aquatic Panda](https://attack.mitre.org/groups/G0143) used rundll32.exe to proxy execution of a malicious DLL file identified as a keylogging binary.(Citation: Crowdstrike HuntReport 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de6db2bf-4ccf-4103-83a5-424ca960fede`.
