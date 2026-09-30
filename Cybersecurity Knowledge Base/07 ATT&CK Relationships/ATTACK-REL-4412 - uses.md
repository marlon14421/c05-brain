---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0108"
target_object: "T1027.013"
stix_relationship_id: "relationship--85aecc08-dda1-4203-9dec-376f1d9d3cad"
---
# Relationship 4412: G0108 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0108 - Blue Mockingbird|G0108: Blue Mockingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Blue Mockingbird](https://attack.mitre.org/groups/G0108) has obfuscated the wallet address in the payload binary.(Citation: RedCanary Mockingbird May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85aecc08-dda1-4203-9dec-376f1d9d3cad`.
