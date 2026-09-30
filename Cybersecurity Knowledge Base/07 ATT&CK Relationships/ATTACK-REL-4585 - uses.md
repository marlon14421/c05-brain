---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1622"
stix_relationship_id: "relationship--9ce98ef3-1951-460b-93c6-2ded0edc8dfd"
---
# Relationship 4585: G0129 — uses → T1622

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1622 - Debugger Evasion|T1622: Debugger Evasion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has embedded debug strings with messages to distract analysts.(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also made calls to Windows API `CheckRemoteDebuggerPresent` and exits if it detects a debugger.(Citation: Sophos Mustang Panda PLUGX)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9ce98ef3-1951-460b-93c6-2ded0edc8dfd`.
