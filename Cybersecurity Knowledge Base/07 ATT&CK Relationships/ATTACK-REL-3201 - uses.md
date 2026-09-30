---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1140"
stix_relationship_id: "relationship--0924ca96-c26b-4bd1-8c50-d3c1a9e1e25b"
---
# Relationship 3201: S1078 — uses → T1140

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RotaJakiro](https://attack.mitre.org/software/S1078) uses the AES algorithm, bit shifts in a function called `rotate`, and an XOR cipher to decrypt resources required for persistence, process guarding, and file locking. It also performs this same function on encrypted stack strings and the `head` and `key` sections in the network packet structure used for C2 communications.(Citation: RotaJakiro 2021 netlab360 analysis)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0924ca96-c26b-4bd1-8c50-d3c1a9e1e25b`.
