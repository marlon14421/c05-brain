---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0049"
target_object: "T1070.007"
stix_relationship_id: "relationship--2c374f4d-e32c-4676-be99-2265d60bced7"
---
# Relationship 2144: DET0049 — detects → T1070.007

**Source object:** [[01 ATT&CK/DET0049 - Behavioral Detection of Network History and Configuration Tampering|DET0049: Behavioral Detection of Network History and Configuration Tampering]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1070.007 - Clear Network Connection History and Configurations|T1070.007: Clear Network Connection History and Configurations]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2c374f4d-e32c-4676-be99-2265d60bced7`.
