---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0666"
target_object: "T1071.001"
stix_relationship_id: "relationship--cf13b1fe-9653-4256-8ca9-d736470d53ec"
---
# Relationship 3728: S0666 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0666 - Gelsemium|S0666: Gelsemium]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gelsemium](https://attack.mitre.org/software/S0666) can use HTTP/S in C2 communications.(Citation: ESET Gelsemium June 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf13b1fe-9653-4256-8ca9-d736470d53ec`.
