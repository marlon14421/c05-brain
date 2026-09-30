---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1044"
target_object: "T1574.001"
stix_relationship_id: "relationship--92764952-45ad-4cfc-a426-c6baefc9974c"
---
# Relationship 0602: M1044 — mitigates → T1574.001

**Source object:** [[01 ATT&CK/M1044 - Restrict Library Loading|M1044: Restrict Library Loading]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disallow loading of remote DLLs. This is included by default in Windows Server 2012+ and is available by patch for XP+ and Server 2003+.(Citation: Microsoft More information about DLL) Enable Safe DLL Search Mode to move the user's current folder later in the search order. This is included by default in modern versions of Windows; the associated Windows Registry key is located at HKLM\SYSTEM\CurrentControlSet\Control\Session Manager\SafeDLLSearchMode .(Citation: Microsoft Dynamic Link Library Search Order)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--92764952-45ad-4cfc-a426-c6baefc9974c`.
