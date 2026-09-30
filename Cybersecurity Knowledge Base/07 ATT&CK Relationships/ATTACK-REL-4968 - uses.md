---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0691"
target_object: "T1016"
stix_relationship_id: "relationship--bf496f91-6737-453e-a8e8-a1d80e0e8dd0"
---
# Relationship 4968: S0691 — uses → T1016

**Source object:** [[01 ATT&CK/S0691 - Neoichor|S0691: Neoichor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Neoichor](https://attack.mitre.org/software/S0691) can gather the IP address from an infected host.(Citation: Microsoft NICKEL December 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf496f91-6737-453e-a8e8-a1d80e0e8dd0`.
