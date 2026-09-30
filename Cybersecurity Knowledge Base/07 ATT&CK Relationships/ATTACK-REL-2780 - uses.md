---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0603"
target_object: "T1210"
stix_relationship_id: "relationship--4f2bd19b-f0f4-4946-a7a5-4947be3346b1"
---
# Relationship 2780: S0603 — uses → T1210

**Source object:** [[01 ATT&CK/S0603 - Stuxnet|S0603: Stuxnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Stuxnet](https://attack.mitre.org/software/S0603) propagates using the MS10-061 Print Spooler and MS08-067 Windows Server Service vulnerabilities.(Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4f2bd19b-f0f4-4946-a7a5-4947be3346b1`.
