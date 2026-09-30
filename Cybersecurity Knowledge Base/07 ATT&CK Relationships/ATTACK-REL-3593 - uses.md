---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0002"
target_object: "T1588.001"
stix_relationship_id: "relationship--113fbb20-8dd7-4ba6-b5a8-486e46d9abeb"
---
# Relationship 3593: C0002 — uses → T1588.001

**Source object:** [[01 ATT&CK/C0002 - Night Dragon|C0002: Night Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.001 - Malware|T1588.001: Malware]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Night Dragon](https://attack.mitre.org/campaigns/C0002), threat actors used Trojans from underground hacker websites.(Citation: McAfee Night Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--113fbb20-8dd7-4ba6-b5a8-486e46d9abeb`.
