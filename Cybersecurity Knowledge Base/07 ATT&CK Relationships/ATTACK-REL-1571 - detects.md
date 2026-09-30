---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0412"
target_object: "T1552"
stix_relationship_id: "relationship--9a673d77-b594-4115-9ffa-b1b38cf6de18"
---
# Relationship 1571: DET0412 — detects → T1552

**Source object:** [[01 ATT&CK/DET0412 - Detect Access or Search for Unsecured Credentials Across Platforms|DET0412: Detect Access or Search for Unsecured Credentials Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1552 - Unsecured Credentials|T1552: Unsecured Credentials]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9a673d77-b594-4115-9ffa-b1b38cf6de18`.
