---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0630"
target_object: "T1106"
stix_relationship_id: "relationship--777c4c38-9da2-4473-b5d0-61f175014760"
---
# Relationship 3924: S0630 — uses → T1106

**Source object:** [[01 ATT&CK/S0630 - Nebulae|S0630: Nebulae]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Nebulae](https://attack.mitre.org/software/S0630) has the ability to use CreateProcess to execute a process.(Citation: Bitdefender Naikon April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--777c4c38-9da2-4473-b5d0-61f175014760`.
