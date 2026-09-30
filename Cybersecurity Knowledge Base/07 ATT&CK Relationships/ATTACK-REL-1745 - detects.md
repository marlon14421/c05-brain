---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0103"
target_object: "T1070.005"
stix_relationship_id: "relationship--b414a54d-8cd1-42e7-92b8-4b4f1460ec6a"
---
# Relationship 1745: DET0103 — detects → T1070.005

**Source object:** [[01 ATT&CK/DET0103 - Behavioral Detection of Network Share Connection Removal via CLI and SMB Disconnects|DET0103: Behavioral Detection of Network Share Connection Removal via CLI and SMB Disconnects]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1070.005 - Network Share Connection Removal|T1070.005: Network Share Connection Removal]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b414a54d-8cd1-42e7-92b8-4b4f1460ec6a`.
