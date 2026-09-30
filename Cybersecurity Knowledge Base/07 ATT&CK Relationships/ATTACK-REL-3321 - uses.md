---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1593"
stix_relationship_id: "relationship--fac15889-5e75-4d1d-b624-294581c299ca"
---
# Relationship 3321: G0034 — uses → T1593

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1593 - Search Open Websites-Domains|T1593: Search Open Websites/Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) researched Ukraine's unique legal entity identifier (called an "EDRPOU" number), including running queries on the EDRPOU website, in preparation for the [NotPetya](https://attack.mitre.org/software/S0368) attack. [Sandworm Team](https://attack.mitre.org/groups/G0034) has also researched third-party websites to help it craft credible spearphishing emails.(Citation: US District Court Indictment GRU Unit 74455 October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fac15889-5e75-4d1d-b624-294581c299ca`.
