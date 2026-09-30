---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0550"
target_object: "T1213.004"
stix_relationship_id: "relationship--b5df0d2d-e827-43ef-b683-3b8aa71bf331"
---
# Relationship 1815: DET0550 — detects → T1213.004

**Source object:** [[01 ATT&CK/DET0550 - Detecting Suspicious Access to CRM Data in SaaS Environments|DET0550: Detecting Suspicious Access to CRM Data in SaaS Environments]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1213.004 - Customer Relationship Management Software|T1213.004: Customer Relationship Management Software]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5df0d2d-e827-43ef-b683-3b8aa71bf331`.
