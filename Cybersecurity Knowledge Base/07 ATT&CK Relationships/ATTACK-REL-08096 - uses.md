---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1082"
stix_relationship_id: "relationship--f7f1c7c3-192b-4675-815d-0a61b3e3a206"
---
# Relationship 8096: G0034 — uses → T1082

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) used a backdoor to enumerate information about the infected system's operating system.(Citation: ESET Telebots July 2017)(Citation: US District Court Indictment GRU Unit 74455 October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f7f1c7c3-192b-4675-815d-0a61b3e3a206`.
