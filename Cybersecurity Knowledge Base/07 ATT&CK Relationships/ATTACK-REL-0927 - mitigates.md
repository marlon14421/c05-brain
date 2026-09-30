---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1026"
target_object: "T1021.007"
stix_relationship_id: "relationship--dd49738c-ba78-41bb-a459-65e89d3faf2a"
---
# Relationship 0927: M1026 — mitigates → T1021.007

**Source object:** [[01 ATT&CK/M1026 - Privileged Account Management|M1026: Privileged Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1021.007 - Cloud Services|T1021.007: Cloud Services]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit the number of high-privileged domain and cloud accounts, and ensure that these are not used for day-to-day operations. Ensure that on-premises accounts do not have privileged cloud permissions and that isolated, cloud-only accounts are used for managing cloud environments.(Citation: Protecting Microsoft 365 From On-Premises Attacks)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd49738c-ba78-41bb-a459-65e89d3faf2a`.
