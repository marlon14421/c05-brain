---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0100"
target_object: "T1218.010"
stix_relationship_id: "relationship--cab50f6d-3621-4429-8c9a-803df15f4e75"
---
# Relationship 3911: G0100 — uses → T1218.010

**Source object:** [[01 ATT&CK/G0100 - Inception|G0100: Inception]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Inception](https://attack.mitre.org/groups/G0100) has ensured persistence at system boot by setting the value regsvr32 %path%\ctfmonrn.dll /s .(Citation: Kaspersky Cloud Atlas December 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cab50f6d-3621-4429-8c9a-803df15f4e75`.
