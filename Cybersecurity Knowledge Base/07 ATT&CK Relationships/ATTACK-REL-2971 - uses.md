---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9037"
target_object: "T1622"
stix_relationship_id: "relationship--a64c7c7d-f08c-40a3-802b-e25fe9eaea6c"
---
# Relationship 2971: S9037 — uses → T1622

**Source object:** [[01 ATT&CK/S9037 - RustyWater|S9037: RustyWater]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1622 - Debugger Evasion|T1622: Debugger Evasion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RustyWater](https://attack.mitre.org/software/S9037) has registered a Vectored Exception Handler (VEH) to catch debugging efforts.(Citation: CloudSEK_RustyWater_Jan2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a64c7c7d-f08c-40a3-802b-e25fe9eaea6c`.
