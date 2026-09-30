---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1200"
target_object: "T1030"
stix_relationship_id: "relationship--727a1214-1098-4639-8482-5d6d8718de76"
---
# Relationship 4899: S1200 — uses → T1030

**Source object:** [[01 ATT&CK/S1200 - StealBit|S1200: StealBit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1030 - Data Transfer Size Limits|T1030: Data Transfer Size Limits]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StealBit](https://attack.mitre.org/software/S1200) can be configured to exfiltrate files at a specified rate to evade network detection mechanisms.(Citation: Cybereason StealBit Exfiltration Tool)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--727a1214-1098-4639-8482-5d6d8718de76`.
