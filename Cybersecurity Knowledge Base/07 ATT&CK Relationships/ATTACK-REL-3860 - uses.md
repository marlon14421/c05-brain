---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1086"
target_object: "T1059.005"
stix_relationship_id: "relationship--20740afb-283e-4143-ab47-685d4c73beda"
---
# Relationship 3860: S1086 — uses → T1059.005

**Source object:** [[01 ATT&CK/S1086 - Snip3|S1086: Snip3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Snip3](https://attack.mitre.org/software/S1086) can use visual basic scripts for first-stage execution.(Citation: Morphisec Snip3 May 2021)(Citation: Telefonica Snip3 December 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20740afb-283e-4143-ab47-685d4c73beda`.
