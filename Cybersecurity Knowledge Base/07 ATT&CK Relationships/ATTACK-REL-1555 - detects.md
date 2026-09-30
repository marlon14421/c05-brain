---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0266"
target_object: "T1070.008"
stix_relationship_id: "relationship--36707c40-9a27-4d62-8bcb-2ad419b3fa2d"
---
# Relationship 1555: DET0266 — detects → T1070.008

**Source object:** [[01 ATT&CK/DET0266 - Behavioral Detection of Mailbox Data and Log Deletion for Anti-Forensics|DET0266: Behavioral Detection of Mailbox Data and Log Deletion for Anti-Forensics]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1070.008 - Clear Mailbox Data|T1070.008: Clear Mailbox Data]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36707c40-9a27-4d62-8bcb-2ad419b3fa2d`.
