---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0067"
target_object: "T1547.001"
stix_relationship_id: "relationship--0500bac5-bc50-4529-ae5f-b4e1a85fa7d7"
---
# Relationship 3672: G0067 — uses → T1547.001

**Source object:** [[01 ATT&CK/G0067 - APT37|G0067: APT37]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT37](https://attack.mitre.org/groups/G0067)'s has added persistence via the Registry key HKCU\Software\Microsoft\CurrentVersion\Run\ .(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0500bac5-bc50-4529-ae5f-b4e1a85fa7d7`.
