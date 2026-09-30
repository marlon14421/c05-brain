---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0369"
target_object: "T1059.004"
stix_relationship_id: "relationship--7d20cbaf-a154-4192-9a97-ef2662d07246"
---
# Relationship 4530: S0369 — uses → T1059.004

**Source object:** [[01 ATT&CK/S0369 - CoinTicker|S0369: CoinTicker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.004 - Unix Shell|T1059.004: Unix Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CoinTicker](https://attack.mitre.org/software/S0369) executes a bash script to establish a reverse shell.(Citation: CoinTicker 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d20cbaf-a154-4192-9a97-ef2662d07246`.
