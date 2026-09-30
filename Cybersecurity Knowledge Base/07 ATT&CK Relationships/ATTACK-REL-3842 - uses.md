---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0026"
target_object: "T1105"
stix_relationship_id: "relationship--882c68e3-5f01-4438-a430-ff22692d8910"
---
# Relationship 3842: G0026 — uses → T1105

**Source object:** [[01 ATT&CK/G0026 - APT18|G0026: APT18]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT18](https://attack.mitre.org/groups/G0026) can upload a file to the victim’s machine.(Citation: PaloAlto DNS Requests May 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--882c68e3-5f01-4438-a430-ff22692d8910`.
