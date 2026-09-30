---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0660"
target_object: "T1497.003"
stix_relationship_id: "relationship--26802b94-95bf-4d01-a552-81069e62131a"
---
# Relationship 2859: S0660 — uses → T1497.003

**Source object:** [[01 ATT&CK/S0660 - Clambling|S0660: Clambling]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.003 - Time Based Checks|T1497.003: Time Based Checks]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Clambling](https://attack.mitre.org/software/S0660) can wait 30 minutes before initiating contact with C2.(Citation: Trend Micro DRBControl February 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26802b94-95bf-4d01-a552-81069e62131a`.
