---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0055"
target_object: "T1105"
stix_relationship_id: "relationship--4bf364ad-1e9c-4860-93c0-241da4c81068"
---
# Relationship 2872: S0055 — uses → T1105

**Source object:** [[01 ATT&CK/S0055 - RARSTONE|S0055: RARSTONE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RARSTONE](https://attack.mitre.org/software/S0055) downloads its backdoor component from a C2 server and loads it directly into memory.(Citation: Aquino RARSTONE)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4bf364ad-1e9c-4860-93c0-241da4c81068`.
