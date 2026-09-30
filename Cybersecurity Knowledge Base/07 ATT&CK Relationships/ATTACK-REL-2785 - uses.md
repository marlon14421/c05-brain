---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1207"
target_object: "T1583.001"
stix_relationship_id: "relationship--cca0443d-fc8c-469e-a32e-a1297497337a"
---
# Relationship 2785: S1207 — uses → T1583.001

**Source object:** [[01 ATT&CK/S1207 - XLoader|S1207: XLoader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[XLoader](https://attack.mitre.org/software/S1207) can utilize hardcoded command and control domain configurations created by the XLoader authors. These are designed to mimic domain registrars and hosting service providers such as Hostinger and Namecheap.(Citation: CheckPoint XLoader 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cca0443d-fc8c-469e-a32e-a1297497337a`.
