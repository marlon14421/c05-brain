---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1140"
stix_relationship_id: "relationship--a6ddb76d-4317-4cfd-9e1d-57d8a0c5fb21"
---
# Relationship 2951: G0045 — uses → T1140

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) has used [certutil](https://attack.mitre.org/software/S0160) in a macro to decode base64-encoded content contained in a dropper document attached to an email. The group has also used certutil -decode to decode files on the victim’s machine when dropping [UPPERCUT](https://attack.mitre.org/software/S0275).(Citation: Accenture Hogfish April 2018)(Citation: FireEye APT10 Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6ddb76d-4317-4cfd-9e1d-57d8a0c5fb21`.
