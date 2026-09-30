---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1027.013"
stix_relationship_id: "relationship--3afd226c-934f-44fd-8194-9a6dee5cba59"
---
# Relationship 4227: G0032 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has used multiple types of encryption and encoding for their payloads, including AES, Caracachs, RC4, XOR, Base64, and other tricks such as creating aliases in code for [Native API](https://attack.mitre.org/techniques/T1106) function names.(Citation: Novetta Blockbuster)(Citation: Novetta Blockbuster Loaders)(Citation: Novetta Blockbuster RATs)(Citation: McAfee Lazarus Resurfaces Feb 2018)(Citation: TrendMicro macOS Dacls May 2020)(Citation: Lazarus APT January 2022)(Citation: Qualys LolZarus)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3afd226c-934f-44fd-8194-9a6dee5cba59`.
