---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1036.003"
stix_relationship_id: "relationship--6441d8c3-861f-4ce3-9121-809d2b0d173b"
---
# Relationship 4448: G0032 — uses → T1036.003

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.003 - Rename Legitimate Utilities|T1036.003: Rename Legitimate Utilities]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has renamed system utilities such as wscript.exe and mshta.exe .(Citation: Qualys LolZarus)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6441d8c3-861f-4ce3-9121-809d2b0d173b`.
