---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1027.013"
stix_relationship_id: "relationship--3b4e29f6-e040-431e-a6e9-a6a3f4e43ce5"
---
# Relationship 3695: S1207 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) features encrypted functions using the RC4 algorithm and bytecode operations.(Citation: Zscaler XLoader 2025)(Citation: ANY.RUN XLoader 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b4e29f6-e040-431e-a6e9-a6a3f4e43ce5`.
