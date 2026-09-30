---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0634"
target_object: "T1059.003"
stix_relationship_id: "relationship--8d3690aa-f2aa-41ba-b0ec-3ecbb24b92ef"
---
# Relationship 2984: S0634 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0634 - EnvyScout|S0634: EnvyScout]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EnvyScout](https://attack.mitre.org/software/S0634) can use cmd.exe to execute malicious files on compromised hosts.(Citation: MSTIC Nobelium Toolset May 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d3690aa-f2aa-41ba-b0ec-3ecbb24b92ef`.
