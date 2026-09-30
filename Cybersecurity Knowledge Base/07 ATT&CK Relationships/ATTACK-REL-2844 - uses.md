---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0233"
target_object: "T1018"
stix_relationship_id: "relationship--05ee7ead-dfe8-4cd2-9e7c-8f1aada9bcde"
---
# Relationship 2844: S0233 — uses → T1018

**Source object:** [[01 ATT&CK/S0233 - MURKYTOP|S0233: MURKYTOP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MURKYTOP](https://attack.mitre.org/software/S0233) has the capability to identify remote hosts on connected networks.(Citation: FireEye Periscope March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--05ee7ead-dfe8-4cd2-9e7c-8f1aada9bcde`.
