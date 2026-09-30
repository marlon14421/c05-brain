---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1027.013"
stix_relationship_id: "relationship--998650da-f301-46be-ab18-38d14359530b"
---
# Relationship 2904: G0045 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) has encoded strings in its malware with base64 as well as with a simple, single-byte XOR obfuscation using key 0x40.(Citation: Accenture Hogfish April 2018)(Citation: FireEye APT10 Sept 2018)(Citation: Symantec Cicada November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--998650da-f301-46be-ab18-38d14359530b`.
