---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0257"
target_object: "T1123"
stix_relationship_id: "relationship--2c219416-4576-4215-80ac-1aebfadefd8b"
---
# Relationship 3195: S0257 — uses → T1123

**Source object:** [[01 ATT&CK/S0257 - VERMIN|S0257: VERMIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VERMIN](https://attack.mitre.org/software/S0257) can perform audio capture.(Citation: Unit 42 VERMIN Jan 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c219416-4576-4215-80ac-1aebfadefd8b`.
