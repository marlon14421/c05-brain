---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1098.002"
stix_relationship_id: "relationship--f212430d-160e-4676-b541-8a7cb818fe6f"
---
# Relationship 1376: M1042 — mitigates → T1098.002

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098.002 - Additional Email Delegate Permissions|T1098.002: Additional Email Delegate Permissions]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

If email delegation is not required, disable it. In Google Workspace this can be accomplished through the Google Admin console.(Citation: Gmail Delegation)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f212430d-160e-4676-b541-8a7cb818fe6f`.
