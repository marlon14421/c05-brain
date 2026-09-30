---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0500"
target_object: "T1213.002"
stix_relationship_id: "relationship--3dbd21a3-71d4-41e3-b999-a9dbbe8dfc91"
---
# Relationship 1513: DET0500 — detects → T1213.002

**Source object:** [[01 ATT&CK/DET0500 - Detecting Abnormal SharePoint Data Mining by Privileged or Rare Users|DET0500: Detecting Abnormal SharePoint Data Mining by Privileged or Rare Users]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1213.002 - Sharepoint|T1213.002: Sharepoint]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3dbd21a3-71d4-41e3-b999-a9dbbe8dfc91`.
