---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1036"
target_object: "T1648"
stix_relationship_id: "relationship--1790e922-4472-4509-8193-63ba613ce068"
---
# Relationship 0179: M1036 — mitigates → T1648

**Source object:** [[01 ATT&CK/M1036 - Account Use Policies|M1036: Account Use Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1648 - Serverless Execution|T1648: Serverless Execution]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Where possible, consider restricting access to and use of serverless functions. For examples, conditional access policies can be applied to users attempting to create workflows in Microsoft Power Automate. Google Apps Scripts that use OAuth can be limited by restricting access to high-risk OAuth scopes.(Citation: Microsoft Developer Support Power Apps Conditional Access)(Citation: Google Workspace Apps Script Restrict OAuth Scopes)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1790e922-4472-4509-8193-63ba613ce068`.
