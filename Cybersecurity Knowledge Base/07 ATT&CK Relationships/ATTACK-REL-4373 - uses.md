---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0086"
target_object: "T1560.002"
stix_relationship_id: "relationship--32568a57-ff9c-42f5-9b60-0b78d7b0a7c0"
---
# Relationship 4373: S0086 — uses → T1560.002

**Source object:** [[01 ATT&CK/S0086 - ZLib|S0086: ZLib]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.002 - Archive via Library|T1560.002: Archive via Library]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [ZLib](https://attack.mitre.org/software/S0086) backdoor compresses communications using the standard Zlib compression library.(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--32568a57-ff9c-42f5-9b60-0b78d7b0a7c0`.
