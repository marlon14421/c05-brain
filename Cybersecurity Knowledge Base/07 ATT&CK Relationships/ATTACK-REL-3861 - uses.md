---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0400"
target_object: "T1070.005"
stix_relationship_id: "relationship--56b6a1b5-b7ec-4974-baf1-9e4565ce5b78"
---
# Relationship 3861: S0400 — uses → T1070.005

**Source object:** [[01 ATT&CK/S0400 - RobbinHood|S0400: RobbinHood]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.005 - Network Share Connection Removal|T1070.005: Network Share Connection Removal]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RobbinHood](https://attack.mitre.org/software/S0400) disconnects all network shares from the computer with the command net use * /DELETE /Y .(Citation: CarbonBlack RobbinHood May 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56b6a1b5-b7ec-4974-baf1-9e4565ce5b78`.
