---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0586"
target_object: "T1018"
stix_relationship_id: "relationship--07324f90-f7c1-41f7-8d08-3ecec98bbe5c"
---
# Relationship 3575: S0586 — uses → T1018

**Source object:** [[01 ATT&CK/S0586 - TAINTEDSCRIBE|S0586: TAINTEDSCRIBE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [TAINTEDSCRIBE](https://attack.mitre.org/software/S0586) command and execution module can perform target system enumeration.(Citation: CISA MAR-10288834-2.v1 TAINTEDSCRIBE MAY 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07324f90-f7c1-41f7-8d08-3ecec98bbe5c`.
