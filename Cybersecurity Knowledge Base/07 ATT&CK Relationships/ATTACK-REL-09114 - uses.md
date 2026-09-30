---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1568"
stix_relationship_id: "relationship--74554e53-92bd-4707-8e1a-ae3904ec935e"
---
# Relationship 9114: G0094 — uses → T1568

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used Dynamic DNS (DDNS) services, such as FreeDNS or No-IP DDNS, to include servers located in South Korea.(Citation: NaumaanProofpoint_GlobalClickFix_April2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74554e53-92bd-4707-8e1a-ae3904ec935e`.
