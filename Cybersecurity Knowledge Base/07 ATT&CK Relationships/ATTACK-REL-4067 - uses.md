---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0470"
target_object: "T1027.003"
stix_relationship_id: "relationship--3811b12a-fcfc-47d2-83ec-89df60ca4c21"
---
# Relationship 4067: S0470 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0470 - BBK|S0470: BBK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BBK](https://attack.mitre.org/software/S0470) can extract a malicious Portable Executable (PE) from a photo.(Citation: Trend Micro Tick November 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3811b12a-fcfc-47d2-83ec-89df60ca4c21`.
