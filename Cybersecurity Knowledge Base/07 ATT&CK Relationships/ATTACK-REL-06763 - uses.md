---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0035"
target_object: "T1584.008"
stix_relationship_id: "relationship--5898ba12-3f7f-4891-96b5-a1d464487013"
---
# Relationship 6763: C0035 — uses → T1584.008

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.008 - Network Devices|T1584.008: Network Devices]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) focuses on compromise of small office-home office (SOHO) network devices to build the subsequent botnet.(Citation: Lumen KVBotnet 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5898ba12-3f7f-4891-96b5-a1d464487013`.
