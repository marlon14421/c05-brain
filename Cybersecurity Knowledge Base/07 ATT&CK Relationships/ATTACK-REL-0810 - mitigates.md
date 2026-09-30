---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1564.008"
stix_relationship_id: "relationship--3b2ca38e-351d-4595-8ddb-17b648f196ef"
---
# Relationship 0810: M1047 — mitigates → T1564.008

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564.008 - Email Hiding Rules|T1564.008: Email Hiding Rules]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enterprise email solutions may have monitoring mechanisms that may include the ability to audit inbox rules on a regular basis. In an Exchange environment, Administrators can use `Get-InboxRule` / `Remove-InboxRule` and `Get-TransportRule` / `Remove-TransportRule` to discover and remove potentially malicious inbox and transport rules.(Citation: Microsoft Get-InboxRule)(Citation: Microsoft Manage Mail Flow Rules 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b2ca38e-351d-4595-8ddb-17b648f196ef`.
