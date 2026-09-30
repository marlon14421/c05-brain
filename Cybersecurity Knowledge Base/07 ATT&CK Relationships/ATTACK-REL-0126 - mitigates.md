---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1045"
target_object: "T1554"
stix_relationship_id: "relationship--685da2a8-4205-4773-982b-5954393c70f8"
---
# Relationship 0126: M1045 — mitigates → T1554

**Source object:** [[01 ATT&CK/M1045 - Code Signing|M1045: Code Signing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure all application component binaries are signed by the correct application developers.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--685da2a8-4205-4773-982b-5954393c70f8`.
