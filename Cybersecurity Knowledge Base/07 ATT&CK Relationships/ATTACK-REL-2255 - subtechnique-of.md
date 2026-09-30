---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "subtechnique-of"
source_object: "T1588.006"
target_object: "T1588"
stix_relationship_id: "relationship--1b7c7b5c-22df-4713-be96-818a8916e6d1"
---
# Relationship 2255: T1588.006 — subtechnique-of → T1588

**Source object:** [[01 ATT&CK/T1588.006 - Vulnerabilities|T1588.006: Vulnerabilities]]  
**Relationship:** `subtechnique-of`  
**Target object:** [[01 ATT&CK/T1588 - Obtain Capabilities|T1588: Obtain Capabilities]]

## Meaning for defensive analysis

Places a more specific technique beneath its parent technique in the ATT&CK taxonomy.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1b7c7b5c-22df-4713-be96-818a8916e6d1`.
