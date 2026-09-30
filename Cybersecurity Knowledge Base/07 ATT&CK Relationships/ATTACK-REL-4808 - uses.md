---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1056"
stix_relationship_id: "relationship--244a8358-96fb-41ce-9cc3-c4899a6f4de4"
---
# Relationship 4808: S1245 — uses → T1056

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056 - Input Capture|T1056: Input Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has collected mouse and keyboard events using “pyWinhook”.(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--244a8358-96fb-41ce-9cc3-c4899a6f4de4`.
