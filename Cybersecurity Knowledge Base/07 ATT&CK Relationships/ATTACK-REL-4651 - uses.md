---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1134.003"
stix_relationship_id: "relationship--76b2e00d-78bb-4aea-a787-46289b8540ef"
---
# Relationship 4651: G1016 — uses → T1134.003

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.003 - Make and Impersonate Token|T1134.003: Make and Impersonate Token]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has utilized tools such as Incognito V2 for token manipulation and impersonation.(Citation: Sygnia Elephant Beetle Jan 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76b2e00d-78bb-4aea-a787-46289b8540ef`.
