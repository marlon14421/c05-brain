---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0496"
target_object: "T1480.002"
stix_relationship_id: "relationship--715faca6-f933-45b5-bb56-45cedf9dd18c"
---
# Relationship 4769: S0496 — uses → T1480.002

**Source object:** [[01 ATT&CK/S0496 - REvil|S0496: REvil]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480.002 - Mutual Exclusion|T1480.002: Mutual Exclusion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[REvil](https://attack.mitre.org/software/S0496) attempts to create a mutex using a hard-coded value to ensure that no other instances of itself are running on the host.(Citation: SecureWorks September 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--715faca6-f933-45b5-bb56-45cedf9dd18c`.
