---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0134"
target_object: "T1001.001"
stix_relationship_id: "relationship--0e27ebb3-2d48-48f6-ab99-968c0a992c61"
---
# Relationship 4515: S0134 — uses → T1001.001

**Source object:** [[01 ATT&CK/S0134 - Downdelph|S0134: Downdelph]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Downdelph](https://attack.mitre.org/software/S0134) inserts pseudo-random characters between each original character during encoding of C2 network requests, making it difficult to write signatures on them.(Citation: ESET Sednit Part 3)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e27ebb3-2d48-48f6-ab99-968c0a992c61`.
