---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0257"
target_object: "T1553.005"
stix_relationship_id: "relationship--7e5a5d4c-3fb4-4db0-9c42-f7345d4a208a"
---
# Relationship 2028: DET0257 — detects → T1553.005

**Source object:** [[01 ATT&CK/DET0257 - Detect Mark-of-the-Web (MOTW) Bypass via Container and Disk Image Files|DET0257: Detect Mark-of-the-Web (MOTW) Bypass via Container and Disk Image Files]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553.005 - Mark-of-the-Web Bypass|T1553.005: Mark-of-the-Web Bypass]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e5a5d4c-3fb4-4db0-9c42-f7345d4a208a`.
