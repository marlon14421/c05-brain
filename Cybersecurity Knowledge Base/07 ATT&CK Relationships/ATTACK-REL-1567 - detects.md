---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0381"
target_object: "T1552.006"
stix_relationship_id: "relationship--d2a5aaa1-4faf-4b37-be23-bd1fcc7cd58a"
---
# Relationship 1567: DET0381 — detects → T1552.006

**Source object:** [[01 ATT&CK/DET0381 - Detect Access and Decryption of Group Policy Preference (GPP) Credentials in SYSVOL|DET0381: Detect Access and Decryption of Group Policy Preference (GPP) Credentials in SYSVOL]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1552.006 - Group Policy Preferences|T1552.006: Group Policy Preferences]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2a5aaa1-4faf-4b37-be23-bd1fcc7cd58a`.
