---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0253"
target_object: "T1547.001"
stix_relationship_id: "relationship--7d1d4ffd-7c60-4a83-bcfa-66413bbe7212"
---
# Relationship 4182: S0253 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0253 - RunningRAT|S0253: RunningRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RunningRAT](https://attack.mitre.org/software/S0253) adds itself to the Registry key Software\Microsoft\Windows\CurrentVersion\Run to establish persistence upon reboot.(Citation: McAfee Gold Dragon)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d1d4ffd-7c60-4a83-bcfa-66413bbe7212`.
