---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0035"
target_object: "T1055.009"
stix_relationship_id: "relationship--85e909bd-e5c0-423d-b3cd-410dad3b8b91"
---
# Relationship 6756: C0035 — uses → T1055.009

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.009 - Proc Memory|T1055.009: Proc Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) final payload installation includes mounting and binding to the \/proc\/ filepath on the victim system to enable subsequent operation in memory while also removing on-disk artifacts.(Citation: Lumen KVBotnet 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--85e909bd-e5c0-423d-b3cd-410dad3b8b91`.
