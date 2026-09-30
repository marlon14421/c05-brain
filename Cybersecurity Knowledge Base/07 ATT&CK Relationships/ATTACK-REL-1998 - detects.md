---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0362"
target_object: "T1546.009"
stix_relationship_id: "relationship--e4e45e24-c4de-45b9-bf54-762269aec2eb"
---
# Relationship 1998: DET0362 — detects → T1546.009

**Source object:** [[01 ATT&CK/DET0362 - Detection Strategy for AppCert DLLs Persistence via Registry Injection|DET0362: Detection Strategy for AppCert DLLs Persistence via Registry Injection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.009 - AppCert DLLs|T1546.009: AppCert DLLs]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e4e45e24-c4de-45b9-bf54-762269aec2eb`.
