---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0498"
target_object: "T1573"
stix_relationship_id: "relationship--0d6e04e8-8e4c-4ef6-ab6a-12ddb498e93a"
---
# Relationship 4811: S0498 — uses → T1573

**Source object:** [[01 ATT&CK/S0498 - Cryptoistic|S0498: Cryptoistic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573 - Encrypted Channel|T1573: Encrypted Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cryptoistic](https://attack.mitre.org/software/S0498) can engage in encrypted communications with C2.(Citation: SentinelOne Lazarus macOS July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d6e04e8-8e4c-4ef6-ab6a-12ddb498e93a`.
