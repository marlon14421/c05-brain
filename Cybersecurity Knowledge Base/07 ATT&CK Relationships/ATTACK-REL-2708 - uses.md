---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0633"
target_object: "T1001.002"
stix_relationship_id: "relationship--41b7f3d7-b42e-4301-ac9e-ecad27e826a0"
---
# Relationship 2708: S0633 — uses → T1001.002

**Source object:** [[01 ATT&CK/S0633 - Sliver|S0633: Sliver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.002 - Steganography|T1001.002: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sliver](https://attack.mitre.org/software/S0633) can encode binary data into a .PNG file for C2 communication.(Citation: GitHub Sliver HTTP)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41b7f3d7-b42e-4301-ac9e-ecad27e826a0`.
