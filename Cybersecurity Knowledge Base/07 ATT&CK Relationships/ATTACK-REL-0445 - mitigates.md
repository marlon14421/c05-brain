---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1025"
target_object: "T1547.008"
stix_relationship_id: "relationship--26bc4aac-e7db-426f-af9f-b85fa60df277"
---
# Relationship 0445: M1025 — mitigates → T1547.008

**Source object:** [[01 ATT&CK/M1025 - Privileged Process Integrity|M1025: Privileged Process Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.008 - LSASS Driver|T1547.008: LSASS Driver]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 8.1 and Server 2012 R2, enable LSA Protection by setting the Registry key HKEY_LOCAL_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Lsa\\RunAsPPL to dword:00000001 . (Citation: Microsoft LSA Protection Mar 2014) LSA Protection ensures that LSA plug-ins and drivers are only loaded if they are digitally signed with a Microsoft signature and adhere to the Microsoft Security Development Lifecycle (SDL) process guidance.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26bc4aac-e7db-426f-af9f-b85fa60df277`.
