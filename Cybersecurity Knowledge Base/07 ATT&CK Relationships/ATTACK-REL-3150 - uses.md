---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0455"
target_object: "T1105"
stix_relationship_id: "relationship--de745ef4-59a0-470c-95c9-5043a717dc54"
---
# Relationship 3150: S0455 — uses → T1105

**Source object:** [[01 ATT&CK/S0455 - Metamorfo|S0455: Metamorfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Metamorfo](https://attack.mitre.org/software/S0455) has used MSI files to download additional files to execute.(Citation: Medium Metamorfo Apr 2020)(Citation: FireEye Metamorfo Apr 2018)(Citation: Fortinet Metamorfo Feb 2020)(Citation: ESET Casbaneiro Oct 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de745ef4-59a0-470c-95c9-5043a717dc54`.
