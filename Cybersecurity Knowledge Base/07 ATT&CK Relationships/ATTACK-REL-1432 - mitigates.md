---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1098.001"
stix_relationship_id: "relationship--fb4099dc-c44a-49c4-b12e-5e58a5635bf4"
---
# Relationship 1432: M1042 — mitigates → T1098.001

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098.001 - Additional Cloud Credentials|T1098.001: Additional Cloud Credentials]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Remove unnecessary and potentially abusable authentication mechanisms where possible. For example, in Entra ID environments, disable the app password feature unless explicitly required.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb4099dc-c44a-49c4-b12e-5e58a5635bf4`.
