---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1070.004"
stix_relationship_id: "relationship--7867218e-78a0-41cf-ada0-8400285b8a1d"
---
# Relationship 3617: G0034 — uses → T1070.004

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has used backdoors that can delete files used in an attack from an infected system.(Citation: ESET Telebots Dec 2016)(Citation: ESET Telebots July 2017)(Citation: Mandiant-Sandworm-Ukraine-2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7867218e-78a0-41cf-ada0-8400285b8a1d`.
