---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0349"
target_object: "T1555.001"
stix_relationship_id: "relationship--b32c6aa0-9299-4ada-a626-9805ba1f1610"
---
# Relationship 3878: S0349 — uses → T1555.001

**Source object:** [[01 ATT&CK/S0349 - LaZagne|S0349: LaZagne]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LaZagne](https://attack.mitre.org/software/S0349) can obtain credentials from macOS Keychains.(Citation: GitHub LaZagne Dec 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b32c6aa0-9299-4ada-a626-9805ba1f1610`.
