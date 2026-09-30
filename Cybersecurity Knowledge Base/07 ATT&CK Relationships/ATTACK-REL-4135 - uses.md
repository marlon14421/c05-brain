---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0011"
target_object: "T1057"
stix_relationship_id: "relationship--ced0348f-1bc8-461b-8123-a1b3aeb38e94"
---
# Relationship 4135: S0011 — uses → T1057

**Source object:** [[01 ATT&CK/S0011 - Taidoor|S0011: Taidoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Taidoor](https://attack.mitre.org/software/S0011) can use GetCurrentProcessId for process discovery.(Citation: CISA MAR-10292089-1.v2 TAIDOOR August 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ced0348f-1bc8-461b-8123-a1b3aeb38e94`.
