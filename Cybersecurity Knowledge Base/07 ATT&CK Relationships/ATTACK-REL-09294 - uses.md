---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0035"
target_object: "T1546"
stix_relationship_id: "relationship--bf492c3c-026c-45f3-bdc4-9ea200af2bb4"
---
# Relationship 9294: C0035 — uses → T1546

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546 - Event Triggered Execution|T1546: Event Triggered Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) involves managing events on victim systems via libevent to execute a callback function when any running process contains the following references in their path without also having a reference to bioset : busybox, wget, curl, tftp, telnetd, or lua. If the bioset string is not found, the related process is terminated.(Citation: Lumen KVBotnet 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf492c3c-026c-45f3-bdc4-9ea200af2bb4`.
