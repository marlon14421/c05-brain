---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1146"
target_object: "T1123"
stix_relationship_id: "relationship--fc622e1d-cbbe-4d8e-b184-ebd23581ec71"
---
# Relationship 3626: S1146 — uses → T1123

**Source object:** [[01 ATT&CK/S1146 - MgBot|S1146: MgBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MgBot](https://attack.mitre.org/software/S1146) can capture input and output audio streams from infected devices.(Citation: ESET EvasivePanda 2023)(Citation: Symantec Daggerfly 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fc622e1d-cbbe-4d8e-b184-ebd23581ec71`.
