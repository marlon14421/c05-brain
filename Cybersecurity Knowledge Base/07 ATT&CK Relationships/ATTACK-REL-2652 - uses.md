---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0126"
target_object: "T1124"
stix_relationship_id: "relationship--c7c1411a-42c8-4d7e-9b56-0465370759de"
---
# Relationship 2652: S0126 — uses → T1124

**Source object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ComRAT](https://attack.mitre.org/software/S0126) has checked the victim system's date and time to perform tasks during business hours (9 to 5, Monday to Friday).(Citation: CISA ComRAT Oct 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c7c1411a-42c8-4d7e-9b56-0465370759de`.
