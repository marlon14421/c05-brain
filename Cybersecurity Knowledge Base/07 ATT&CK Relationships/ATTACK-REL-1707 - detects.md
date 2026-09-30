---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0105"
target_object: "T1110.002"
stix_relationship_id: "relationship--4656281a-1d49-4b06-9470-dc81d50dc5fc"
---
# Relationship 1707: DET0105 — detects → T1110.002

**Source object:** [[01 ATT&CK/DET0105 - Post-Credential Dump Password Cracking Detection via Suspicious File Access and Hash |DET0105: Post-Credential Dump Password Cracking Detection via Suspicious File Access and Hash Analysis Tools]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1110.002 - Password Cracking|T1110.002: Password Cracking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4656281a-1d49-4b06-9470-dc81d50dc5fc`.
