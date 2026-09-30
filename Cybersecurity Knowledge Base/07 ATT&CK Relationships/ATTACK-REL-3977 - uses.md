---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0447"
target_object: "T1497.003"
stix_relationship_id: "relationship--76f712e1-cc4c-43a2-b6a7-c288ac206aac"
---
# Relationship 3977: S0447 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0447 - Lokibot|S0447: Lokibot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lokibot](https://attack.mitre.org/software/S0447) has performed a time-based anti-debug check before downloading its third stage.(Citation: Talos Lokibot Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76f712e1-cc4c-43a2-b6a7-c288ac206aac`.
