---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1070"
target_object: "T1497.001"
stix_relationship_id: "relationship--9122a590-4a01-4f41-a15a-bc3bc92b0439"
---
# Relationship 3405: S1070 — uses → T1497.001

**Source object:** [[01 ATT&CK/S1070 - Black Basta|S1070: Black Basta]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Black Basta](https://attack.mitre.org/software/S1070) can check system flags and libraries, process timing, and API's to detect code emulation or sandboxing.(Citation: Palo Alto Networks Black Basta August 2022)(Citation: Check Point Black Basta October 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9122a590-4a01-4f41-a15a-bc3bc92b0439`.
