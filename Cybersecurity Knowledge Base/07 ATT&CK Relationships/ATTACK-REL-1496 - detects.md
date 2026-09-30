---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0222"
target_object: "T1218.014"
stix_relationship_id: "relationship--e79ec747-79ad-4467-ae3b-724da019de1d"
---
# Relationship 1496: DET0222 — detects → T1218.014

**Source object:** [[01 ATT&CK/DET0222 - Detecting MMC (.msc) Proxy Execution and Malicious COM Activation|DET0222: Detecting MMC (.msc) Proxy Execution and Malicious COM Activation]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.014 - MMC|T1218.014: MMC]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e79ec747-79ad-4467-ae3b-724da019de1d`.
