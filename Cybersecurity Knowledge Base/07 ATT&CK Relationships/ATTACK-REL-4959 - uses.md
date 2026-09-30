---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1222"
target_object: "T1082"
stix_relationship_id: "relationship--80c87037-4997-449c-8a92-1183103dda8d"
---
# Relationship 4959: S1222 — uses → T1082

**Source object:** [[01 ATT&CK/S1222 - RIFLESPINE|S1222: RIFLESPINE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RIFLESPINE](https://attack.mitre.org/software/S1222) can collect system information after installation on infected systems.(Citation: Google Cloud Mandiant UNC3886 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80c87037-4997-449c-8a92-1183103dda8d`.
