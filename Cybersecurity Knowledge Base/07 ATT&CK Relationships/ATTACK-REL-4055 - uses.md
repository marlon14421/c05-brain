---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1196"
target_object: "T1071.001"
stix_relationship_id: "relationship--36f66914-f792-4336-8436-dfd3bd349455"
---
# Relationship 4055: S1196 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1196 - Troll Stealer|S1196: Troll Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) uses HTTP to communicate to command and control infrastructure.(Citation: S2W Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36f66914-f792-4336-8436-dfd3bd349455`.
