---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0530"
target_object: "T1021.002"
stix_relationship_id: "relationship--dc3fcfcd-1df7-49fd-8ada-e0081063efea"
---
# Relationship 1510: DET0530 — detects → T1021.002

**Source object:** [[01 ATT&CK/DET0530 - Multi-Event Detection for SMB Admin Share Lateral Movement|DET0530: Multi-Event Detection for SMB Admin Share Lateral Movement]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc3fcfcd-1df7-49fd-8ada-e0081063efea`.
