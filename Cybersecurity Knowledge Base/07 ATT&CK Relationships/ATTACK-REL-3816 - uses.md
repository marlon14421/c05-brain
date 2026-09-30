---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0367"
target_object: "T1135"
stix_relationship_id: "relationship--491dc622-fa43-4015-b24a-8ec8d8f5a376"
---
# Relationship 3816: S0367 — uses → T1135

**Source object:** [[01 ATT&CK/S0367 - Emotet|S0367: Emotet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1135 - Network Share Discovery|T1135: Network Share Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Emotet](https://attack.mitre.org/software/S0367) has enumerated non-hidden network shares using `WNetEnumResourceW`. (Citation: Binary Defense Emotes Wi-Fi Spreader)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--491dc622-fa43-4015-b24a-8ec8d8f5a376`.
