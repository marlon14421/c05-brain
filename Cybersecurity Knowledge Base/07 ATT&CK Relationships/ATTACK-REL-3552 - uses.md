---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0442"
target_object: "T1105"
stix_relationship_id: "relationship--fe3b8cb8-8ff1-4abf-ac98-ce31108e5bb5"
---
# Relationship 3552: S0442 — uses → T1105

**Source object:** [[01 ATT&CK/S0442 - VBShower|S0442: VBShower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VBShower](https://attack.mitre.org/software/S0442) has the ability to download VBS files to the target computer.(Citation: Kaspersky Cloud Atlas August 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe3b8cb8-8ff1-4abf-ac98-ce31108e5bb5`.
