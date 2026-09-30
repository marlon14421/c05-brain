---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0570"
target_object: "T1567.002"
stix_relationship_id: "relationship--6d01d586-c518-45db-96f3-5b718324c9da"
---
# Relationship 2131: DET0570 — detects → T1567.002

**Source object:** [[01 ATT&CK/DET0570 - Detection Strategy for Exfiltration to Cloud Storage|DET0570: Detection Strategy for Exfiltration to Cloud Storage]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6d01d586-c518-45db-96f3-5b718324c9da`.
