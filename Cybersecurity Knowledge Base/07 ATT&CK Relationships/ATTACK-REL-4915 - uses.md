---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0534"
target_object: "T1036.007"
stix_relationship_id: "relationship--d667c620-28cb-4c86-83f7-33d6c154369c"
---
# Relationship 4915: S0534 — uses → T1036.007

**Source object:** [[01 ATT&CK/S0534 - Bazar|S0534: Bazar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.007 - Double File Extension|T1036.007: Double File Extension]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [Bazar](https://attack.mitre.org/software/S0534) loader has used dual-extension executable files such as PreviewReport.DOC.exe.(Citation: Cybereason Bazar July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d667c620-28cb-4c86-83f7-33d6c154369c`.
