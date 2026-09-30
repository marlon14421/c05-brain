---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1147"
target_object: "T1102"
stix_relationship_id: "relationship--01e1f755-740d-4744-ac81-4f6300b6c857"
---
# Relationship 4889: S1147 — uses → T1102

**Source object:** [[01 ATT&CK/S1147 - Nightdoor|S1147: Nightdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Nightdoor](https://attack.mitre.org/software/S1147) can utilize Microsoft OneDrive or Google Drive for command and control purposes.(Citation: ESET EvasivePanda 2024)(Citation: Symantec Daggerfly 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--01e1f755-740d-4744-ac81-4f6300b6c857`.
