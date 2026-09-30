---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0569"
target_object: "T1105"
stix_relationship_id: "relationship--a4e88205-c591-4bad-9daa-0bf8f6049c57"
---
# Relationship 3005: S0569 — uses → T1105

**Source object:** [[01 ATT&CK/S0569 - Explosive|S0569: Explosive]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Explosive](https://attack.mitre.org/software/S0569) has a function to download a file to the infected system.(Citation: CheckPoint Volatile Cedar March 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a4e88205-c591-4bad-9daa-0bf8f6049c57`.
