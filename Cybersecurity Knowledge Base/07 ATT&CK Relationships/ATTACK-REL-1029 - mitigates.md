---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1666"
stix_relationship_id: "relationship--cad0af31-8ca1-431d-a0c1-7d2f468fc5fa"
---
# Relationship 1029: M1047 — mitigates → T1666

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1666 - Modify Cloud Resource Hierarchy|T1666: Modify Cloud Resource Hierarchy]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Periodically audit resource groups in the cloud management console to ensure that only expected items exist, especially close to the top of the hierarchy (e.g., AWS accounts and Azure subscriptions). Typically, top-level accounts (such as the AWS management account) should not contain any workloads or resources.(Citation: AWS Management Account Best Practices)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cad0af31-8ca1-431d-a0c1-7d2f468fc5fa`.
