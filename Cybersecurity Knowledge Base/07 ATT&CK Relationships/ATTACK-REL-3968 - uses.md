---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0686"
target_object: "T1105"
stix_relationship_id: "relationship--16446d10-cf55-4e1e-bbf8-7ce6b8a2fb2b"
---
# Relationship 3968: S0686 — uses → T1105

**Source object:** [[01 ATT&CK/S0686 - QuietSieve|S0686: QuietSieve]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[QuietSieve](https://attack.mitre.org/software/S0686) can download and execute payloads on a target host.(Citation: Microsoft Actinium February 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16446d10-cf55-4e1e-bbf8-7ce6b8a2fb2b`.
