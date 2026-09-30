---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1596"
stix_relationship_id: "relationship--0b98a770-5e21-467a-a2c4-adbad2c04e16"
---
# Relationship 2775: G0007 — uses → T1596

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1596 - Search Open Technical Databases|T1596: Search Open Technical Databases]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used large language models (LLMs) to assist in script development and deployment.(Citation: MSFT-AI)(Citation: OpenAI-CTI)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b98a770-5e21-467a-a2c4-adbad2c04e16`.
