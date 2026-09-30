---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0228"
target_object: "T1071.004"
stix_relationship_id: "relationship--aae339ae-44bb-48d3-b62e-7f35376bb974"
---
# Relationship 4131: S0228 — uses → T1071.004

**Source object:** [[01 ATT&CK/S0228 - NanHaiShu|S0228: NanHaiShu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NanHaiShu](https://attack.mitre.org/software/S0228) uses DNS for the C2 communications.(Citation: fsecure NanHaiShu July 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aae339ae-44bb-48d3-b62e-7f35376bb974`.
