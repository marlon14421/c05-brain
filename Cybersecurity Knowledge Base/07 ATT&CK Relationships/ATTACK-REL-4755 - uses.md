---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0165"
target_object: "T1087.001"
stix_relationship_id: "relationship--30c5a160-c42d-4bee-bcc6-b85f083136d7"
---
# Relationship 4755: S0165 — uses → T1087.001

**Source object:** [[01 ATT&CK/S0165 - OSInfo|S0165: OSInfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.001 - Local Account|T1087.001: Local Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OSInfo](https://attack.mitre.org/software/S0165) enumerates local and domain users(Citation: Symantec Buckeye)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--30c5a160-c42d-4bee-bcc6-b85f083136d7`.
