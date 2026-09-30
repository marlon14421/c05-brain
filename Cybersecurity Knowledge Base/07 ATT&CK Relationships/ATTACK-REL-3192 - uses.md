---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0384"
target_object: "T1106"
stix_relationship_id: "relationship--19e06de9-b9a1-4532-94c6-f729036ba0c3"
---
# Relationship 3192: S0384 — uses → T1106

**Source object:** [[01 ATT&CK/S0384 - Dridex|S0384: Dridex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dridex](https://attack.mitre.org/software/S0384) has used the OutputDebugStringW function to avoid malware analysis as part of its anti-debugging technique.(Citation: Checkpoint Dridex Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19e06de9-b9a1-4532-94c6-f729036ba0c3`.
