---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0040"
target_object: "T1593.002"
stix_relationship_id: "relationship--6b8397d1-7b3a-4b37-8758-578822a30eca"
---
# Relationship 4020: C0040 — uses → T1593.002

**Source object:** [[01 ATT&CK/C0040 - APT41 DUST|C0040: APT41 DUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1593.002 - Search Engines|T1593.002: Search Engines]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT41 DUST](https://attack.mitre.org/campaigns/C0040) involved use of search engines to research victim servers.(Citation: Google Cloud APT41 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b8397d1-7b3a-4b37-8758-578822a30eca`.
