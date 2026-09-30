---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0093"
target_object: "T1033"
stix_relationship_id: "relationship--8fdf3a18-e1c3-4db4-8f68-15121c910826"
---
# Relationship 1969: DET0093 — detects → T1033

**Source object:** [[01 ATT&CK/DET0093 - Behavioral Detection of User Discovery via Local and Remote Enumeration|DET0093: Behavioral Detection of User Discovery via Local and Remote Enumeration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8fdf3a18-e1c3-4db4-8f68-15121c910826`.
