---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0137"
target_object: "T1588.002"
stix_relationship_id: "relationship--ba29bbf3-4947-4676-98c4-13bf6fb79ce0"
---
# Relationship 2795: G0137 — uses → T1588.002

**Source object:** [[01 ATT&CK/G0137 - Ferocious Kitten|G0137: Ferocious Kitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ferocious Kitten](https://attack.mitre.org/groups/G0137) has obtained open source tools for its operations, including JsonCPP and Psiphon.(Citation: Kaspersky Ferocious Kitten Jun 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba29bbf3-4947-4676-98c4-13bf6fb79ce0`.
