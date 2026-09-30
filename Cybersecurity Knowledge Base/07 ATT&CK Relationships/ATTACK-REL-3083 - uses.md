---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "S1053"
stix_relationship_id: "relationship--6ccac8cb-9e5f-4031-bf27-4ced4a1672d2"
---
# Relationship 3083: C0018 — uses → S1053

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1053 - AvosLocker|S1053: AvosLocker]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0018](https://attack.mitre.org/campaigns/C0018), the threat actors used [AvosLocker](https://attack.mitre.org/software/S1053) ransomware to encrypt the compromised network.(Citation: Costa AvosLocker May 2022)(Citation: Cisco Talos Avos Jun 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ccac8cb-9e5f-4031-bf27-4ced4a1672d2`.
