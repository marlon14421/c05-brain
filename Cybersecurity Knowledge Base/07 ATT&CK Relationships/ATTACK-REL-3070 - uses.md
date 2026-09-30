---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0240"
target_object: "T1106"
stix_relationship_id: "relationship--44b2a372-1aee-4a7e-a544-2aacdfe3121a"
---
# Relationship 3070: S0240 — uses → T1106

**Source object:** [[01 ATT&CK/S0240 - ROKRAT|S0240: ROKRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ROKRAT](https://attack.mitre.org/software/S0240) can use a variety of API calls to execute shellcode.(Citation: Malwarebytes RokRAT VBA January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44b2a372-1aee-4a7e-a544-2aacdfe3121a`.
