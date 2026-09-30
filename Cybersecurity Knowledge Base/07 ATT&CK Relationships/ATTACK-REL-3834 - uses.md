---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1198"
target_object: "T1573"
stix_relationship_id: "relationship--1532b910-6bf8-4622-a183-0bb7fd18c4ae"
---
# Relationship 3834: S1198 — uses → T1573

**Source object:** [[01 ATT&CK/S1198 - Gomir|S1198: Gomir]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573 - Encrypted Channel|T1573: Encrypted Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gomir](https://attack.mitre.org/software/S1198) uses a custom encryption algorithm for content sent to command and control infrastructure.(Citation: Symantec Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1532b910-6bf8-4622-a183-0bb7fd18c4ae`.
