---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1014"
target_object: "T1564.001"
stix_relationship_id: "relationship--17bb48d5-7b1b-43be-b18e-07bc0462cad5"
---
# Relationship 4071: G1014 — uses → T1564.001

**Source object:** [[01 ATT&CK/G1014 - LuminousMoth|G1014: LuminousMoth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malware to store malicious binaries in hidden directories on victim's USB drives.(Citation: Kaspersky LuminousMoth July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--17bb48d5-7b1b-43be-b18e-07bc0462cad5`.
