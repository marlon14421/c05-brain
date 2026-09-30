---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "S1010"
stix_relationship_id: "relationship--61869a8e-d6da-478a-b770-47f97beae8b4"
---
# Relationship 3587: G0034 — uses → S1010

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1010 - VPNFilter|S1010: VPNFilter]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VPNFilter](https://attack.mitre.org/software/S1010) is associated with [Sandworm Team](https://attack.mitre.org/groups/G0034) operations based on reporting on [VPNFilter](https://attack.mitre.org/software/S1010) replacement software, [Cyclops Blink](https://attack.mitre.org/software/S0687).(Citation: NCSC CISA Cyclops Blink Advisory February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--61869a8e-d6da-478a-b770-47f97beae8b4`.
