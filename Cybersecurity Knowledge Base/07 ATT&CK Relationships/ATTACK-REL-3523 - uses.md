---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1213"
target_object: "T1547.001"
stix_relationship_id: "relationship--827bdd59-c6b9-43fe-9004-ab9a740e323a"
---
# Relationship 3523: S1213 — uses → T1547.001

**Source object:** [[01 ATT&CK/S1213 - Lumma Stealer|S1213: Lumma Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Lumma Stealer](https://attack.mitre.org/software/S1213) has created registry keys to maintain persistence using `HKCU:\SOFTWARE\Microsoft\Windows\CurrentVersion\Run`.(Citation: Cybereason LumaStealer Undated)(Citation: Netskope LummaStealer 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--827bdd59-c6b9-43fe-9004-ab9a740e323a`.
