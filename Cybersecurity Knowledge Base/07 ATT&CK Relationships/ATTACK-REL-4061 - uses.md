---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0236"
target_object: "T1036.004"
stix_relationship_id: "relationship--abdf9690-d578-4f86-a2cc-295c2789bb4e"
---
# Relationship 4061: S0236 — uses → T1036.004

**Source object:** [[01 ATT&CK/S0236 - Kwampirs|S0236: Kwampirs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kwampirs](https://attack.mitre.org/software/S0236) establishes persistence by adding a new service with the display name "WMI Performance Adapter Extension" in an attempt to masquerade as a legitimate WMI service.(Citation: Symantec Orangeworm April 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--abdf9690-d578-4f86-a2cc-295c2789bb4e`.
