---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0340"
target_object: "T1204.004"
stix_relationship_id: "relationship--733c50f9-bc54-4eb0-9cd7-7fa341a4613d"
---
# Relationship 1962: DET0340 — detects → T1204.004

**Source object:** [[01 ATT&CK/DET0340 - User Execution – Malicious Copy & Paste (browser-email → shell with obfuscated one-li|DET0340: User Execution – Malicious Copy & Paste (browser/email → shell with obfuscated one-liner) – T1204.004]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1204.004 - Malicious Copy and Paste|T1204.004: Malicious Copy and Paste]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--733c50f9-bc54-4eb0-9cd7-7fa341a4613d`.
