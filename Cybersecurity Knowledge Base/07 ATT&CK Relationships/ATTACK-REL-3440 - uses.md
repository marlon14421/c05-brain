---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1151"
target_object: "T1068"
stix_relationship_id: "relationship--2d61c23b-df1a-4d90-affa-b37a55b5e941"
---
# Relationship 3440: S1151 — uses → T1068

**Source object:** [[01 ATT&CK/S1151 - ZeroCleare|S1151: ZeroCleare]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZeroCleare](https://attack.mitre.org/software/S1151) has used a vulnerable signed VBoxDrv driver to bypass Microsoft Driver Signature Enforcement (DSE) protections and subsequently load the unsigned [RawDisk](https://attack.mitre.org/software/S0364) driver.(Citation: IBM ZeroCleare Wiper December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2d61c23b-df1a-4d90-affa-b37a55b5e941`.
