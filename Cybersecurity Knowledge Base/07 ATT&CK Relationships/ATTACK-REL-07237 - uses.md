---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0035"
target_object: "T1564.013"
stix_relationship_id: "relationship--b6c8454f-57ab-45a6-9b69-1794b17a860f"
---
# Relationship 7237: C0035 — uses → T1564.013

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.013 - Bind Mounts|T1564.013: Bind Mounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) leveraged a bind mount to bind itself to the `/proc/` file path before deleting its files from the `/tmp/` directory.(Citation: Lumen KVBotnet 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6c8454f-57ab-45a6-9b69-1794b17a860f`.
