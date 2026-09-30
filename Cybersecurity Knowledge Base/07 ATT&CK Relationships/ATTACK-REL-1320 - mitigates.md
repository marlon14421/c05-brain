---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1666"
stix_relationship_id: "relationship--3dd8c9cd-e9ad-4f3e-a4a6-0d4ff0904980"
---
# Relationship 1320: M1054 — mitigates → T1666

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1666 - Modify Cloud Resource Hierarchy|T1666: Modify Cloud Resource Hierarchy]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

In Azure environments, consider setting a policy to block subscription transfers.(Citation: Azure Subscription Policies) In AWS environments, consider using Service Control Policies to prevent the use of the `LeaveOrganization` API call.(Citation: AWS RE:Inforce Threat Detection 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3dd8c9cd-e9ad-4f3e-a4a6-0d4ff0904980`.
