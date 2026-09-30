---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0889"
target_object: "T1590.006"
stix_relationship_id: "relationship--8a96c70f-1562-4f85-9002-6d7a989c32d8"
---
# Relationship 1771: DET0889 — detects → T1590.006

**Source object:** [[01 ATT&CK/DET0889 - Detection of Network Security Appliances|DET0889: Detection of Network Security Appliances]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1590.006 - Network Security Appliances|T1590.006: Network Security Appliances]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a96c70f-1562-4f85-9002-6d7a989c32d8`.
