---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1114.003"
stix_relationship_id: "relationship--cd1a91ea-4b59-4352-b902-941fbec64f29"
---
# Relationship 0079: M1047 — mitigates → T1114.003

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1114.003 - Email Forwarding Rule|T1114.003: Email Forwarding Rule]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Enterprise email solutions have monitoring mechanisms that may include the ability to audit auto-forwarding rules on a regular basis. In an Exchange environment, Administrators can use `Get-InboxRule` / `Remove-InboxRule` and `Get-TransportRule` / `Remove-TransportRule` to discover and remove potentially malicious auto-fowarding and transport rules.(Citation: Microsoft Tim McMichael Exchange Mail Forwarding 2)(Citation: Microsoft Manage Mail Flow Rules 2023)(Citation: Microsoft Get-InboxRule) In addition to this, a MAPI Editor can be utilized to examine the underlying database structure and discover any modifications/tampering of the properties of auto-forwarding rules.(Citation: Pfammatter - Hidden Inbox Rules)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd1a91ea-4b59-4352-b902-941fbec64f29`.
