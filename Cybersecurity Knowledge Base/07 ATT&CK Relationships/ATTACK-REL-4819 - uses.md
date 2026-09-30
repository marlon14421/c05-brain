---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1568.001"
stix_relationship_id: "relationship--50b623c1-828f-4a2b-bb9e-38600b071563"
---
# Relationship 4819: G0045 — uses → T1568.001

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.001 - Fast Flux DNS|T1568.001: Fast Flux DNS]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) has used dynamic DNS service providers to host malicious domains.(Citation: District Court of NY APT10 Indictment December 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50b623c1-828f-4a2b-bb9e-38600b071563`.
