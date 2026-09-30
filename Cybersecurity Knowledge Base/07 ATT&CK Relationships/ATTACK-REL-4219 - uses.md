---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0681"
target_object: "T1055.001"
stix_relationship_id: "relationship--410ec59e-9e11-4acc-98d6-4d7c63f09c8d"
---
# Relationship 4219: S0681 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0681 - Lizar|S0681: Lizar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lizar](https://attack.mitre.org/software/S0681) has used the PowerKatz plugin that can be loaded into the address space of a PowerShell process through reflective DLL loading.(Citation: BiZone Lizar May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--410ec59e-9e11-4acc-98d6-4d7c63f09c8d`.
