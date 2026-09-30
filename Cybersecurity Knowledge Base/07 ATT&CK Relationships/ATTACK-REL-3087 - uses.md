---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0233"
target_object: "T1046"
stix_relationship_id: "relationship--db85ce33-98cf-4fec-93bd-402909cbe4bc"
---
# Relationship 3087: S0233 — uses → T1046

**Source object:** [[01 ATT&CK/S0233 - MURKYTOP|S0233: MURKYTOP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MURKYTOP](https://attack.mitre.org/software/S0233) has the capability to scan for open ports on hosts in a connected network.(Citation: FireEye Periscope March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--db85ce33-98cf-4fec-93bd-402909cbe4bc`.
