---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1055.001"
stix_relationship_id: "relationship--4bcd21d2-7583-4b82-8d33-2b153eeb6fdb"
---
# Relationship 4830: S0194 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194) contains a collection of CodeExecution modules that inject code (DLL, shellcode) into a process.(Citation: GitHub PowerSploit May 2012)(Citation: PowerSploit Documentation)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4bcd21d2-7583-4b82-8d33-2b153eeb6fdb`.
