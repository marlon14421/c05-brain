---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1021.003"
stix_relationship_id: "relationship--eb21bd35-77bb-4bc4-868d-b6e0940375ca"
---
# Relationship 0068: M1026 — mitigates → T1021.003

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021.003 - Distributed Component Object Model|T1021.003: Distributed Component Object Model]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Modify Registry settings (directly or using Dcomcnfg.exe) in `HKEY_LOCAL_MACHINE\SOFTWARE\Classes\AppID\{{AppID_GUID}}` associated with the process-wide security of individual COM applications.(Citation: Microsoft Process Wide Com Keys) Modify Registry settings (directly or using Dcomcnfg.exe) in `HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Ole` associated with system-wide security defaults for all COM applications that do not set their own process-wide security.(Citation: Microsoft System Wide Com Keys) (Citation: Microsoft COM ACL)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb21bd35-77bb-4bc4-868d-b6e0940375ca`.
