---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1090.003"
stix_relationship_id: "relationship--186ee163-fb1f-4a7d-b7d9-3c01efbb2be0"
---
# Relationship 4345: S0386 — uses → T1090.003

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has used [Tor](https://attack.mitre.org/software/S0183) for C2.(Citation: NJCCIC Ursnif Sept 2016)(Citation: ProofPoint Ursnif Aug 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--186ee163-fb1f-4a7d-b7d9-3c01efbb2be0`.
