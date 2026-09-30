---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0457"
target_object: "T1059.001"
stix_relationship_id: "relationship--998ad8ac-9929-4360-92c8-63efb1a81d78"
---
# Relationship 2709: S0457 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0457 - Netwalker|S0457: Netwalker]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Netwalker](https://attack.mitre.org/software/S0457) has been written in PowerShell and executed directly in memory, avoiding detection.(Citation: TrendMicro Netwalker May 2020)(Citation: Sophos Netwalker May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--998ad8ac-9929-4360-92c8-63efb1a81d78`.
