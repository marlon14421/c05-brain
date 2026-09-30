---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1244"
target_object: "T1057"
stix_relationship_id: "relationship--4f368185-2f3f-4a42-b106-707cd476b6b0"
---
# Relationship 2926: S1244 — uses → T1057

**Source object:** [[01 ATT&CK/S1244 - Medusa Ransomware|S1244: Medusa Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Medusa Ransomware](https://attack.mitre.org/software/S1244) has utilized an encoded list of the processes that it detects and terminates.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)(Citation: Broadcom Medusa Ransomware Medusa Group March 2025)(Citation: Security Scorecard Medusa Ransomware January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f368185-2f3f-4a42-b106-707cd476b6b0`.
