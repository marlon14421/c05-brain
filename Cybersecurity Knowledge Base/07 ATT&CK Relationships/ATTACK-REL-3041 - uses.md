---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0561"
target_object: "T1547.001"
stix_relationship_id: "relationship--d02d208e-2b9a-4613-bc89-df3953ad9576"
---
# Relationship 3041: S0561 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0561 - GuLoader|S0561: GuLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GuLoader](https://attack.mitre.org/software/S0561) can establish persistence via the Registry under HKCU\Software\Microsoft\Windows\CurrentVersion\RunOnce .(Citation: Unit 42 NETWIRE April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d02d208e-2b9a-4613-bc89-df3953ad9576`.
