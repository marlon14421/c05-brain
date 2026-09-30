---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0543"
target_object: "T1614.001"
stix_relationship_id: "relationship--392980d3-6cac-4740-824c-4911ab10f135"
---
# Relationship 4607: S0543 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0543 - Spark|S0543: Spark]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Spark](https://attack.mitre.org/software/S0543) has checked the results of the GetKeyboardLayoutList and the language name returned by GetLocaleInfoA to make sure they contain the word “Arabic” before executing.(Citation: Unit42 Molerat Mar 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--392980d3-6cac-4740-824c-4911ab10f135`.
