---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0035"
target_object: "T1571"
stix_relationship_id: "relationship--d40daa58-ca17-400c-b488-4508775e55e7"
---
# Relationship 5200: C0035 — uses → T1571

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1571 - Non-Standard Port|T1571: Non-Standard Port]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) generates a random port number greater than 30,000 to serve as the listener for subsequent command and control activity.(Citation: Lumen KVBotnet 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d40daa58-ca17-400c-b488-4508775e55e7`.
