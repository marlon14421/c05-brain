---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1015"
target_object: "T1105"
stix_relationship_id: "relationship--4e39da36-f7e0-4e26-b354-ca34fb801e33"
---
# Relationship 3698: S1015 — uses → T1105

**Source object:** [[01 ATT&CK/S1015 - Milan|S1015: Milan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Milan](https://attack.mitre.org/software/S1015) has received files from C2 and stored them in log folders beginning with the character sequence `a9850d2f`.(Citation: ClearSky Siamesekitten August 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e39da36-f7e0-4e26-b354-ca34fb801e33`.
