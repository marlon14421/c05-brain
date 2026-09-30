---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1025"
target_object: "T1082"
stix_relationship_id: "relationship--a6904fd0-d121-4b26-b05c-1615e3baf599"
---
# Relationship 3883: S1025 — uses → T1082

**Source object:** [[01 ATT&CK/S1025 - Amadey|S1025: Amadey]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Amadey](https://attack.mitre.org/software/S1025) has collected the computer name and OS version from a compromised machine.(Citation: Korean FSI TA505 2020)(Citation: BlackBerry Amadey 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6904fd0-d121-4b26-b05c-1615e3baf599`.
