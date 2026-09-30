---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0200"
target_object: "T1071.001"
stix_relationship_id: "relationship--84e09e1a-b670-427e-8f35-1c472ac7a988"
---
# Relationship 3187: S0200 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0200 - Dipsind|S0200: Dipsind]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Dipsind](https://attack.mitre.org/software/S0200) uses HTTP for C2.(Citation: Microsoft PLATINUM April 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84e09e1a-b670-427e-8f35-1c472ac7a988`.
