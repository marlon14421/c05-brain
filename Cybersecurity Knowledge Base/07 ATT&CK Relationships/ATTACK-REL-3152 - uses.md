---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9023"
target_object: "T1518.001"
stix_relationship_id: "relationship--77a6a1b4-9217-48fe-b1dd-f1f6506dd910"
---
# Relationship 3152: S9023 — uses → T1518.001

**Source object:** [[01 ATT&CK/S9023 - HiddenFace|S9023: HiddenFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HiddenFace](https://attack.mitre.org/software/S9023) can identify processes identified with security applications and tooling.(Citation: ESET HiddenFace 2024)(Citation: Trend Micro Earth Kasha NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77a6a1b4-9217-48fe-b1dd-f1f6506dd910`.
