---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0137"
target_object: "T1680"
stix_relationship_id: "relationship--44150544-030d-430c-bec8-6fb4373d484e"
---
# Relationship 3631: S0137 — uses → T1680

**Source object:** [[01 ATT&CK/S0137 - CORESHELL|S0137: CORESHELL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CORESHELL](https://attack.mitre.org/software/S0137) collects the volume serial number from the victim and sends the information to its C2 server.(Citation: FireEye APT28)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44150544-030d-430c-bec8-6fb4373d484e`.
