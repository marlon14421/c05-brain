---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1583.004"
stix_relationship_id: "relationship--576cbf79-037c-4265-af56-cd0d7a57c1b9"
---
# Relationship 3449: C0014 — uses → T1583.004

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.004 - Server|T1583.004: Server]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [Operation Wocao](https://attack.mitre.org/campaigns/C0014), the threat actors purchased servers with Bitcoin to use during the operation.(Citation: FoxIT Wocao December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--576cbf79-037c-4265-af56-cd0d7a57c1b9`.
