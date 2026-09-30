---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1160"
target_object: "T1518.001"
stix_relationship_id: "relationship--ae8ac860-1dfc-41c3-81ab-08da9619c4a3"
---
# Relationship 2824: S1160 — uses → T1518.001

**Source object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Latrodectus](https://attack.mitre.org/software/S1160) has the ability to identify installed antivirus products.(Citation: Elastic Latrodectus May 2024)(Citation: Bitsight Latrodectus June 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae8ac860-1dfc-41c3-81ab-08da9619c4a3`.
