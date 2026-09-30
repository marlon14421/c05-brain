---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1016"
target_object: "T1059.004"
stix_relationship_id: "relationship--c08ebacd-b5e4-48c3-8ee6-389c635801da"
---
# Relationship 3203: S1016 — uses → T1059.004

**Source object:** [[01 ATT&CK/S1016 - MacMa|S1016: MacMa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MacMa](https://attack.mitre.org/software/S1016) can execute supplied shell commands and uses bash scripts to perform additional actions.(Citation: ESET DazzleSpy Jan 2022)(Citation: Objective-See MacMa Nov 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c08ebacd-b5e4-48c3-8ee6-389c635801da`.
