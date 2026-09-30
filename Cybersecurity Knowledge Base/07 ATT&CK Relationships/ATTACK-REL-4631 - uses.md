---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1081"
target_object: "T1059.001"
stix_relationship_id: "relationship--07ef8045-6a01-4764-a351-a8a2ee2170f7"
---
# Relationship 4631: S1081 — uses → T1059.001

**Source object:** [[01 ATT&CK/S1081 - BADHATCH|S1081: BADHATCH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BADHATCH](https://attack.mitre.org/software/S1081) can utilize `powershell.exe` to execute commands on a compromised host.(Citation: Gigamon BADHATCH Jul 2019)(Citation: BitDefender BADHATCH Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--07ef8045-6a01-4764-a351-a8a2ee2170f7`.
