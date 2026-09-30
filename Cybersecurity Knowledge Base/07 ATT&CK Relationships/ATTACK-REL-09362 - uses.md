---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1055"
target_object: "T1078.004"
stix_relationship_id: "relationship--ae75eacd-4727-40e0-a781-146aa8c1e730"
---
# Relationship 9362: G1055 — uses → T1078.004

**Source object:** [[01 ATT&CK/G1055 - VOID MANTICORE|G1055: VOID MANTICORE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.004 - Cloud Accounts|T1078.004: Cloud Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VOID MANTICORE](https://attack.mitre.org/groups/G1055) has leveraged privileged cloud accounts to access cloud-based management consoles to include Microsoft Intune.(Citation: Palo Alto VOID MANTICORE Iran Cyber Threats March 2026) [VOID MANTICORE](https://attack.mitre.org/groups/G1055) has also compromised existing accounts within the Microsoft Entra ID environment.(Citation: SEC 8-K Stryker Corporation Filing Handala Hack March 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae75eacd-4727-40e0-a781-146aa8c1e730`.
