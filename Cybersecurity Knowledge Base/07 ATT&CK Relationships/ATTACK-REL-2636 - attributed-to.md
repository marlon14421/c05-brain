---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "attributed-to"
source_object: "C0035"
target_object: "G1017"
stix_relationship_id: "relationship--ddbd85c0-2b3a-4311-966b-abc2e658c340"
---
# Relationship 2636: C0035 — attributed-to → G1017

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `attributed-to`  
**Target object:** [[01 ATT&CK/G1017 - Volt Typhoon|G1017: Volt Typhoon]]

## Meaning for defensive analysis

Records an attribution relationship in the source catalog; attribution is probabilistic and should not be treated as certainty.

## Source description

[Volt Typhoon](https://attack.mitre.org/groups/G1017) used [KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) to build intermediate communication chains between operators and victims, such as identified access to victims in Guam.(Citation: Lumen KVBotnet 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ddbd85c0-2b3a-4311-966b-abc2e658c340`.
