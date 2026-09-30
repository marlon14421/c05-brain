---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0363"
target_object: "T1055"
stix_relationship_id: "relationship--85dc96ac-ec8e-4e15-ba4b-807c1a7b46cc"
---
# Relationship 3450: S0363 — uses → T1055

**Source object:** [[01 ATT&CK/S0363 - Empire|S0363: Empire]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Empire](https://attack.mitre.org/software/S0363) contains multiple modules for injecting into processes, such as Invoke-PSInject .(Citation: Github PowerShell Empire)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85dc96ac-ec8e-4e15-ba4b-807c1a7b46cc`.
