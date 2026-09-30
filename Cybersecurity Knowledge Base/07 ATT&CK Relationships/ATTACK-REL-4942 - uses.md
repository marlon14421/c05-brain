---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0124"
target_object: "T1105"
stix_relationship_id: "relationship--ce4707f0-d5b8-4dd6-b5ab-cf1483dd236f"
---
# Relationship 4942: S0124 — uses → T1105

**Source object:** [[01 ATT&CK/S0124 - Pisloader|S0124: Pisloader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pisloader](https://attack.mitre.org/software/S0124) has a command to upload a file to the victim machine.(Citation: Palo Alto DNS Requests)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce4707f0-d5b8-4dd6-b5ab-cf1483dd236f`.
