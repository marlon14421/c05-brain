---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1027"
stix_relationship_id: "relationship--8c9ecd8e-44d6-4e03-84c6-ff6f44b3bc33"
---
# Relationship 4623: S1228 — uses → T1027

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has obfuscated DLL names using the ror13AddHash32 algorithm.(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c9ecd8e-44d6-4e03-84c6-ff6f44b3bc33`.
