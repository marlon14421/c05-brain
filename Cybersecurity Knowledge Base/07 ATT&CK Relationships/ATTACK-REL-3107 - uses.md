---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0013"
target_object: "T1584.004"
stix_relationship_id: "relationship--26bac510-efd4-499c-8272-3cf186d3b4e3"
---
# Relationship 3107: C0013 — uses → T1584.004

**Source object:** [[01 ATT&CK/C0013 - Operation Sharpshooter|C0013: Operation Sharpshooter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.004 - Server|T1584.004: Server]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [Operation Sharpshooter](https://attack.mitre.org/campaigns/C0013), the threat actors compromised a server they used as part of the campaign's infrastructure.(Citation: Bleeping Computer Op Sharpshooter March 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26bac510-efd4-499c-8272-3cf186d3b4e3`.
