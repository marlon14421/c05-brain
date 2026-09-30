---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0073"
target_object: "T1505.003"
stix_relationship_id: "relationship--660d09ce-8722-42b3-8503-911dff37bf22"
---
# Relationship 4419: S0073 — uses → T1505.003

**Source object:** [[01 ATT&CK/S0073 - ASPXSpy|S0073: ASPXSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ASPXSpy](https://attack.mitre.org/software/S0073) is a Web shell. The ASPXTool version used by [Threat Group-3390](https://attack.mitre.org/groups/G0027) has been deployed to accessible servers running Internet Information Services (IIS).(Citation: Dell TG-3390)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--660d09ce-8722-42b3-8503-911dff37bf22`.
