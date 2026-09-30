---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1105"
stix_relationship_id: "relationship--c592bcf5-6e88-4d77-a274-0a58b7388e76"
---
# Relationship 2993: G0129 — uses → T1105

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has downloaded additional executables following the initial infection stage.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: Recorded Future REDDELTA July 2020)(Citation: Sophos PlugX September 2022) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also leveraged Visual Studio Code `code.exe` and Dev Tunnels using `DevTunnel.exe` to propagate additional tools and payloads.(Citation: Unit42 Chinese VSCode 06 September 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c592bcf5-6e88-4d77-a274-0a58b7388e76`.
