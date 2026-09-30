---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0615"
target_object: "T1564.010"
stix_relationship_id: "relationship--6e6fe0e8-fb0f-40b8-bb8c-4c6aba839618"
---
# Relationship 3917: S0615 — uses → T1564.010

**Source object:** [[01 ATT&CK/S0615 - SombRAT|S0615: SombRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.010 - Process Argument Spoofing|T1564.010: Process Argument Spoofing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SombRAT](https://attack.mitre.org/software/S0615) has the ability to modify its process memory to hide process command-line arguments.(Citation: FireEye FiveHands April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e6fe0e8-fb0f-40b8-bb8c-4c6aba839618`.
