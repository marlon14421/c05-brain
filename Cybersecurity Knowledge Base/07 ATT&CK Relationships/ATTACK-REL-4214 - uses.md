---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1153"
target_object: "T1555.001"
stix_relationship_id: "relationship--e14893ce-24b2-41b0-9597-7775e2f71dc5"
---
# Relationship 4214: S1153 — uses → T1555.001

**Source object:** [[01 ATT&CK/S1153 - Cuckoo Stealer|S1153: Cuckoo Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cuckoo Stealer](https://attack.mitre.org/software/S1153) can capture files from a targeted user's keychain directory.(Citation: Kandji Cuckoo April 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e14893ce-24b2-41b0-9597-7775e2f71dc5`.
