---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0018"
target_object: "T1018"
stix_relationship_id: "relationship--7fe49f05-8f96-4fc2-bc5b-b2eea59efca3"
---
# Relationship 2758: S0018 — uses → T1018

**Source object:** [[01 ATT&CK/S0018 - Sykipot|S0018: Sykipot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sykipot](https://attack.mitre.org/software/S0018) may use net view /domain to display hostnames of available systems on a network.(Citation: AlienVault Sykipot 2011)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fe49f05-8f96-4fc2-bc5b-b2eea59efca3`.
