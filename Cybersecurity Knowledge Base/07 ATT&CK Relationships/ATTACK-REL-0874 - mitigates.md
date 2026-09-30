---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1098.003"
stix_relationship_id: "relationship--2606e684-b69d-47fc-822f-279d197a1e7a"
---
# Relationship 0874: M1026 — mitigates → T1098.003

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1098.003 - Additional Cloud Roles|T1098.003: Additional Cloud Roles]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure that all accounts use the least privileges they require. In Azure AD environments, consider using Privileged Identity Management (PIM) to define roles that require two or more approvals before assignment to users.(Citation: Microsoft Requests for Azure AD Roles in Privileged Identity Management)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2606e684-b69d-47fc-822f-279d197a1e7a`.
