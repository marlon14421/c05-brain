---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0632"
target_object: "T1105"
stix_relationship_id: "relationship--494255a0-7672-4302-9e1b-bf3767cb8384"
---
# Relationship 4044: S0632 — uses → T1105

**Source object:** [[01 ATT&CK/S0632 - GrimAgent|S0632: GrimAgent]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GrimAgent](https://attack.mitre.org/software/S0632) has the ability to download and execute additional payloads.(Citation: Group IB GrimAgent July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--494255a0-7672-4302-9e1b-bf3767cb8384`.
