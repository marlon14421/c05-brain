---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0270"
target_object: "T1484"
stix_relationship_id: "relationship--e92bcd91-5617-4283-ba1e-bc100d897064"
---
# Relationship 2052: DET0270 — detects → T1484

**Source object:** [[01 ATT&CK/DET0270 - Detection of Domain or Tenant Policy Modifications via AD and Identity Provider|DET0270: Detection of Domain or Tenant Policy Modifications via AD and Identity Provider]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1484 - Domain or Tenant Policy Modification|T1484: Domain or Tenant Policy Modification]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e92bcd91-5617-4283-ba1e-bc100d897064`.
