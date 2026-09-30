---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0382"
target_object: "T1547.001"
stix_relationship_id: "relationship--62bf46b4-69b3-4a32-bcbb-c9d960e3039a"
---
# Relationship 4620: S0382 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0382 - ServHelper|S0382: ServHelper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ServHelper](https://attack.mitre.org/software/S0382) may attempt to establish persistence via the HKCU\Software\Microsoft\Windows\CurrentVersion\Run\ run key.(Citation: Deep Instinct TA505 Apr 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62bf46b4-69b3-4a32-bcbb-c9d960e3039a`.
