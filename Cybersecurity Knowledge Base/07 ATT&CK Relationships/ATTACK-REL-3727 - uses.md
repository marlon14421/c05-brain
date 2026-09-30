---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0038"
target_object: "T1074.001"
stix_relationship_id: "relationship--611cb6eb-efdb-4d74-b354-5064ab52bd34"
---
# Relationship 3727: S0038 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0038 - Duqu|S0038: Duqu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Modules can be pushed to and executed by [Duqu](https://attack.mitre.org/software/S0038) that copy data to a staging area, compress it, and XOR encrypt it.(Citation: Symantec W32.Duqu)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--611cb6eb-efdb-4d74-b354-5064ab52bd34`.
