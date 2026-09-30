---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1036.005"
stix_relationship_id: "relationship--a90a5b4d-b677-4a69-8fa0-feab294c9daf"
---
# Relationship 4259: C0014 — uses → T1036.005

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), the threat actors renamed some tools and executables to appear as legitimate programs.(Citation: FoxIT Wocao December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a90a5b4d-b677-4a69-8fa0-feab294c9daf`.
