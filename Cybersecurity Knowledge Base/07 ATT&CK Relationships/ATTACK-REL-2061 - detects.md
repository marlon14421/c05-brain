---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0573"
target_object: "T1537"
stix_relationship_id: "relationship--95e5c02b-7101-4399-8d56-b5758c3081a6"
---
# Relationship 2061: DET0573 — detects → T1537

**Source object:** [[01 ATT&CK/DET0573 - Cross-Platform Detection of Data Transfer to Cloud Account|DET0573: Cross-Platform Detection of Data Transfer to Cloud Account]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1537 - Transfer Data to Cloud Account|T1537: Transfer Data to Cloud Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--95e5c02b-7101-4399-8d56-b5758c3081a6`.
