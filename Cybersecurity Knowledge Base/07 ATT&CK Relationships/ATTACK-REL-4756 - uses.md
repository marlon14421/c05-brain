---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0026"
target_object: "T1071.001"
stix_relationship_id: "relationship--d7d7b5e5-aceb-473b-aeaa-f1287d8d0542"
---
# Relationship 4756: G0026 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0026 - APT18|G0026: APT18]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT18](https://attack.mitre.org/groups/G0026) uses HTTP for C2 communications.(Citation: PaloAlto DNS Requests May 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7d7b5e5-aceb-473b-aeaa-f1287d8d0542`.
