---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1047"
target_object: "T1036.005"
stix_relationship_id: "relationship--d9d62a84-34e0-4397-9e88-1a39d29e4e15"
---
# Relationship 2857: G1047 — uses → T1036.005

**Source object:** [[01 ATT&CK/G1047 - Velvet Ant|G1047: Velvet Ant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Velvet Ant](https://attack.mitre.org/groups/G1047) used a malicious DLL, `iviewers.dll`, that mimics the legitimate "OLE/COM Object Viewer" within Windows.(Citation: Sygnia VelvetAnt 2024A)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9d62a84-34e0-4397-9e88-1a39d29e4e15`.
