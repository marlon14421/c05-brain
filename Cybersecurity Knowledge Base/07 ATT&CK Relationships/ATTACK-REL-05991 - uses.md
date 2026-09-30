---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0354"
target_object: "T1574"
stix_relationship_id: "relationship--70ed2026-90af-4236-8180-2c095bbce0fe"
---
# Relationship 5991: S0354 — uses → T1574

**Source object:** [[01 ATT&CK/S0354 - Denis|S0354: Denis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574 - Hijack Execution Flow|T1574: Hijack Execution Flow]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Denis](https://attack.mitre.org/software/S0354) replaces the nonexistent Windows DLL "msfte.dll" with its own malicious version, which is loaded by the SearchIndexer.exe and SearchProtocolHost.exe.(Citation: Cybereason Cobalt Kitty 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70ed2026-90af-4236-8180-2c095bbce0fe`.
