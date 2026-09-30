---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1559.001"
stix_relationship_id: "relationship--26febb57-254c-40cb-b2f4-d2666bf95db2"
---
# Relationship 3030: G0094 — uses → T1559.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.001 - Component Object Model|T1559.001: Component Object Model]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has leveraged Component Object Model (COM) to create scheduled tasks to include using naming conventions that mimic legitimate applications.(Citation: Gen Digital Kimsuky HTTPTroy October 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has leveraged obfuscation VBScript to form a string in `WScript.Shell` which has downloaded a malicious payload to the victim environment.(Citation: Aryaka Kimsuky July 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26febb57-254c-40cb-b2f4-d2666bf95db2`.
