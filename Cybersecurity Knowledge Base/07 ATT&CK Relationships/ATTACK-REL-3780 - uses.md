---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0201"
target_object: "T1222.001"
stix_relationship_id: "relationship--093f8796-b394-490b-8048-115f4ee32959"
---
# Relationship 3780: S0201 — uses → T1222.001

**Source object:** [[01 ATT&CK/S0201 - JPIN|S0201: JPIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1222.001 - Windows Permissions|T1222.001: Windows Permissions]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[JPIN](https://attack.mitre.org/software/S0201) can use the command-line utility cacls.exe to change file permissions.(Citation: Microsoft PLATINUM April 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--093f8796-b394-490b-8048-115f4ee32959`.
