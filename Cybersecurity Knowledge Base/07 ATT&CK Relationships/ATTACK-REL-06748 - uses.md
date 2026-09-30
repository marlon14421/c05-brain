---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0008"
target_object: "S0029"
stix_relationship_id: "relationship--d0f797ce-9176-4b74-8d64-fad4e1bdef4f"
---
# Relationship 6748: G0008 — uses → S0029

**Source object:** [[01 ATT&CK/G0008 - Carbanak|G0008: Carbanak]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0029 - PsExec|S0029: PsExec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: Kaspersky Carbanak)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0f797ce-9176-4b74-8d64-fad4e1bdef4f`.
