---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0182"
target_object: "T1547.001"
stix_relationship_id: "relationship--0f60b67a-c6a5-4855-991e-00ec6fe5f9ac"
---
# Relationship 4251: S0182 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0182 - FinFisher|S0182: FinFisher]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FinFisher](https://attack.mitre.org/software/S0182) establishes persistence by creating the Registry key HKCU\Software\Microsoft\Windows\Run .(Citation: FinFisher Citation)(Citation: Microsoft FinFisher March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f60b67a-c6a5-4855-991e-00ec6fe5f9ac`.
