---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0844"
target_object: "T1587.003"
stix_relationship_id: "relationship--ef33ab11-69aa-46b8-a0a7-f54a0386daff"
---
# Relationship 1636: DET0844 — detects → T1587.003

**Source object:** [[01 ATT&CK/DET0844 - Detection of Digital Certificates|DET0844: Detection of Digital Certificates]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1587.003 - Digital Certificates|T1587.003: Digital Certificates]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef33ab11-69aa-46b8-a0a7-f54a0386daff`.
