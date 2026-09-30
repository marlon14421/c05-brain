---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1573.001"
stix_relationship_id: "relationship--4c06e313-2cde-494c-a8dc-449649a1afa6"
---
# Relationship 6191: G0032 — uses → T1573.001

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Several [Lazarus Group](https://attack.mitre.org/groups/G0032) malware families encrypt C2 traffic using custom code that uses XOR with an ADD operation and XOR with a SUB operation. Another [Lazarus Group](https://attack.mitre.org/groups/G0032) malware sample XORs C2 traffic. Other [Lazarus Group](https://attack.mitre.org/groups/G0032) malware uses Caracachs encryption to encrypt C2 payloads. [Lazarus Group](https://attack.mitre.org/groups/G0032) has also used AES to encrypt C2 traffic.(Citation: Novetta Blockbuster)(Citation: Novetta Blockbuster Destructive Malware)(Citation: McAfee Lazarus Resurfaces Feb 2018)(Citation: McAfee GhostSecret)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c06e313-2cde-494c-a8dc-449649a1afa6`.
