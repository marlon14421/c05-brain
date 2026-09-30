---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0607"
target_object: "T1027"
stix_relationship_id: "relationship--89567fdb-433a-4821-85bb-a4a9f55cfef5"
---
# Relationship 3686: S0607 — uses → T1027

**Source object:** [[01 ATT&CK/S0607 - KillDisk|S0607: KillDisk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KillDisk](https://attack.mitre.org/software/S0607) uses VMProtect to make reverse engineering the malware more difficult.(Citation: Trend Micro KillDisk 1)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--89567fdb-433a-4821-85bb-a4a9f55cfef5`.
