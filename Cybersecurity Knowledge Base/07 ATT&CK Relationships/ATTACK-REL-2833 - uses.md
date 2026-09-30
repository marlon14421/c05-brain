---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9017"
target_object: "T1027.013"
stix_relationship_id: "relationship--b693efc4-a3e5-4378-9aa0-fad7c653e63e"
---
# Relationship 2833: S9017 — uses → T1027.013

**Source object:** [[01 ATT&CK/S9017 - DCRAT|S9017: DCRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [DCRAT](https://attack.mitre.org/software/S9017) configuration file is encrypted using AES-256.(Citation: Zscaler BlindEagle DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b693efc4-a3e5-4378-9aa0-fad7c653e63e`.
