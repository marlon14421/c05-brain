---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0039"
target_object: "T1059.003"
stix_relationship_id: "relationship--13a8be40-1190-4553-b026-58c5088c322a"
---
# Relationship 4253: G0039 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0039 - Suckfly|G0039: Suckfly]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Several tools used by [Suckfly](https://attack.mitre.org/groups/G0039) have been command-line driven.(Citation: Symantec Suckfly May 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13a8be40-1190-4553-b026-58c5088c322a`.
