---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0134"
target_object: "T1574.001"
stix_relationship_id: "relationship--f4f5b6a4-26d5-4352-a25d-001a51a0a121"
---
# Relationship 3242: S0134 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0134 - Downdelph|S0134: Downdelph]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Downdelph](https://attack.mitre.org/software/S0134) uses search order hijacking of the Windows executable sysprep.exe to escalate privileges.(Citation: ESET Sednit Part 3)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4f5b6a4-26d5-4352-a25d-001a51a0a121`.
