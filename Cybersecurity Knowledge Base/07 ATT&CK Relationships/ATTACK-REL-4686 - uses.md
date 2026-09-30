---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1083"
stix_relationship_id: "relationship--f45f18e9-4a0c-4f22-8ef6-5a18314535ea"
---
# Relationship 4686: S0455 — uses → T1083

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) has searched the Program Files directories for specific folders and has searched for strings related to its mutexes.(Citation: Medium Metamorfo Apr 2020)(Citation: Fortinet Metamorfo Feb 2020)(Citation: FireEye Metamorfo Apr 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f45f18e9-4a0c-4f22-8ef6-5a18314535ea`.
