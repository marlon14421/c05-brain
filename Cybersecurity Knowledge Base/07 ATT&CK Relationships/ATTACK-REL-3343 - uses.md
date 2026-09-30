---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1106"
stix_relationship_id: "relationship--2c131932-4632-4866-845f-212cbe29756d"
---
# Relationship 3343: G0032 — uses → T1106

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has used the Windows API ObtainUserAgentString to obtain the User-Agent from a compromised host to connect to a C2 server.(Citation: McAfee Lazarus Jul 2020) [Lazarus Group](https://attack.mitre.org/groups/G0032) has also used various, often lesser known, functions to perform various types of Discovery and [Process Injection](https://attack.mitre.org/techniques/T1055).(Citation: Lazarus APT January 2022)(Citation: Qualys LolZarus)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c131932-4632-4866-845f-212cbe29756d`.
