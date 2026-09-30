---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0484"
target_object: "T1518.001"
stix_relationship_id: "relationship--8121ed43-42eb-42ad-a86f-26fb53b71975"
---
# Relationship 4474: S0484 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0484 - Carberp|S0484: Carberp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Carberp](https://attack.mitre.org/software/S0484) has queried the infected system's registry searching for specific registry keys associated with antivirus products.(Citation: Prevx Carberp March 2011)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8121ed43-42eb-42ad-a86f-26fb53b71975`.
