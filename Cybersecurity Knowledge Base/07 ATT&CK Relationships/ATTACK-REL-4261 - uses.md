---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1087.002"
stix_relationship_id: "relationship--94229aa6-c862-48b8-9959-1e1d3c04dd5e"
---
# Relationship 4261: S0483 — uses → T1087.002

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) can query LDAP and can use built-in `net` commands to identify additional users on the network to infect.(Citation: IBM IcedID November 2017)(Citation: DFIR_Quantum_Ransomware)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94229aa6-c862-48b8-9959-1e1d3c04dd5e`.
