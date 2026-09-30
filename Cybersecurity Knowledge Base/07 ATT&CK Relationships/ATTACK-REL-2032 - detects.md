---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0148"
target_object: "T1606.002"
stix_relationship_id: "relationship--4c734725-c97f-437b-952d-f94f9dba8f05"
---
# Relationship 2032: DET0148 — detects → T1606.002

**Source object:** [[01 ATT&CK/DET0148 - Detection Strategy for Forged SAML Tokens|DET0148: Detection Strategy for Forged SAML Tokens]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1606.002 - SAML Tokens|T1606.002: SAML Tokens]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c734725-c97f-437b-952d-f94f9dba8f05`.
