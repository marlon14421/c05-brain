---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0249"
target_object: "T1033"
stix_relationship_id: "relationship--41634cea-6236-4013-bda3-345bcba4f40f"
---
# Relationship 4866: S0249 — uses → T1033

**Source object:** [[01 ATT&CK/S0249 - Gold Dragon|S0249: Gold Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gold Dragon](https://attack.mitre.org/software/S0249) collects the endpoint victim's username and uses it as a basis for downloading additional components from the C2 server.(Citation: McAfee Gold Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41634cea-6236-4013-bda3-345bcba4f40f`.
