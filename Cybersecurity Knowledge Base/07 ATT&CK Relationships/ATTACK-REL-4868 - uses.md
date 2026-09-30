---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0213"
target_object: "T1105"
stix_relationship_id: "relationship--8f41386c-5760-409e-b8b4-513f3d791d9f"
---
# Relationship 4868: S0213 — uses → T1105

**Source object:** [[01 ATT&CK/S0213 - DOGCALL|S0213: DOGCALL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DOGCALL](https://attack.mitre.org/software/S0213) can download and execute additional payloads.(Citation: Unit 42 Nokki Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f41386c-5760-409e-b8b4-513f3d791d9f`.
