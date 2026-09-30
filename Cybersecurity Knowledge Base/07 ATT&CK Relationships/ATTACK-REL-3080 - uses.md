---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1564.010"
stix_relationship_id: "relationship--41b8a7b7-0134-412d-85d7-3a0141beb8e2"
---
# Relationship 3080: S0154 — uses → T1564.010

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.010 - Process Argument Spoofing|T1564.010: Process Argument Spoofing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) can use spoof arguments in spawned processes that execute beacon commands.(Citation: Cobalt Strike Manual 4.3 November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41b8a7b7-0134-412d-85d7-3a0141beb8e2`.
