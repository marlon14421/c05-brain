---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1620"
stix_relationship_id: "relationship--510616c2-f124-49b2-83a2-cac81d2d4155"
---
# Relationship 4278: G0032 — uses → T1620

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has changed memory protection permissions then overwritten in memory DLL function code with shellcode, which was later executed via [KernelCallbackTable](https://attack.mitre.org/techniques/T1574/013) hijacking. [Lazarus Group](https://attack.mitre.org/groups/G0032) has also used shellcode within macros to decrypt and manually map DLLs into memory at runtime.(Citation: Lazarus APT January 2022)(Citation: Qualys LolZarus)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--510616c2-f124-49b2-83a2-cac81d2d4155`.
