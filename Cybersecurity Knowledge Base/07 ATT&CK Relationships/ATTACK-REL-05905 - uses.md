---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1686.003"
stix_relationship_id: "relationship--de8d46b7-d34d-4ea9-8d49-54eedd104c46"
---
# Relationship 5905: G0032 — uses → T1686.003

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Various [Lazarus Group](https://attack.mitre.org/groups/G0032) malware modifies the Windows firewall to allow incoming connections or disable it entirely using [netsh](https://attack.mitre.org/software/S0108). (Citation: Novetta Blockbuster)(Citation: Novetta Blockbuster Loaders)(Citation: Novetta Blockbuster Tools)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--de8d46b7-d34d-4ea9-8d49-54eedd104c46`.
