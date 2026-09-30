---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0615"
target_object: "T1033"
stix_relationship_id: "relationship--70bed654-4c16-456a-8691-4f2bf1c916cc"
---
# Relationship 4700: S0615 — uses → T1033

**Source object:** [[01 ATT&CK/S0615 - SombRAT|S0615: SombRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SombRAT](https://attack.mitre.org/software/S0615) can execute getinfo to identify the username on a compromised host.(Citation: BlackBerry CostaRicto November 2020)(Citation: CISA AR21-126A FIVEHANDS May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70bed654-4c16-456a-8691-4f2bf1c916cc`.
