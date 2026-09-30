---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9035"
target_object: "T1007"
stix_relationship_id: "relationship--d3d8bcd3-9ea1-4bea-bcce-d8c302680c7a"
---
# Relationship 4736: S9035 — uses → T1007

**Source object:** [[01 ATT&CK/S9035 - LAMEHUG|S9035: LAMEHUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LAMEHUG](https://attack.mitre.org/software/S9035) can gather service information on targeted systems.(Citation: Nov AI Threat Tracker)(Citation: Cato LAMEHUG JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3d8bcd3-9ea1-4bea-bcce-d8c302680c7a`.
