---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1063"
target_object: "T1518.001"
stix_relationship_id: "relationship--81e6eb4d-4a94-4416-8a45-b54e9cafda9d"
---
# Relationship 3452: S1063 — uses → T1518.001

**Source object:** [[01 ATT&CK/S1063 - Brute Ratel C4|S1063: Brute Ratel C4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Brute Ratel C4](https://attack.mitre.org/software/S1063) can detect EDR userland hooks.(Citation: Palo Alto Brute Ratel July 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81e6eb4d-4a94-4416-8a45-b54e9cafda9d`.
