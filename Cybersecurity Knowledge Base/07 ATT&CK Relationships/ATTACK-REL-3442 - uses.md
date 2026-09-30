---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0330"
target_object: "T1055.002"
stix_relationship_id: "relationship--da69efe7-e99e-4d79-a455-c59f4c087b22"
---
# Relationship 3442: S0330 — uses → T1055.002

**Source object:** [[01 ATT&CK/S0330 - Zeus Panda|S0330: Zeus Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.002 - Portable Executable Injection|T1055.002: Portable Executable Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Zeus Panda](https://attack.mitre.org/software/S0330) checks processes on the system and if they meet the necessary requirements, it injects into that process.(Citation: GDATA Zeus Panda June 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da69efe7-e99e-4d79-a455-c59f4c087b22`.
