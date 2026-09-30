---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0230"
target_object: "T1082"
stix_relationship_id: "relationship--7bb2d594-36dc-458d-9f9b-8a3df42fac67"
---
# Relationship 4220: S0230 — uses → T1082

**Source object:** [[01 ATT&CK/S0230 - ZeroT|S0230: ZeroT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZeroT](https://attack.mitre.org/software/S0230) gathers the victim's computer name, Windows version, and system language, and then sends it to its C2 server.(Citation: Proofpoint ZeroT Feb 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7bb2d594-36dc-458d-9f9b-8a3df42fac67`.
