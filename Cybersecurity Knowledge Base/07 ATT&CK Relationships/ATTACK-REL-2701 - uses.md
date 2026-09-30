---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0454"
target_object: "T1123"
stix_relationship_id: "relationship--721b7c0a-4774-4b09-882f-be7ba1cab7a5"
---
# Relationship 2701: S0454 — uses → T1123

**Source object:** [[01 ATT&CK/S0454 - Cadelspy|S0454: Cadelspy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1123 - Audio Capture|T1123: Audio Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cadelspy](https://attack.mitre.org/software/S0454) has the ability to record audio from the compromised host.(Citation: Symantec Chafer Dec 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--721b7c0a-4774-4b09-882f-be7ba1cab7a5`.
