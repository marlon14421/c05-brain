---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1102.002"
stix_relationship_id: "relationship--d66da21d-1a8c-4b32-b700-f1d3d938b57e"
---
# Relationship 8773: G0034 — uses → T1102.002

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has used the Telegram Bot API from Telegram Messenger to send and receive commands to its Python backdoor. [Sandworm Team](https://attack.mitre.org/groups/G0034) also used legitimate M.E.Doc software update check requests for sending and receiving commands and hosted malicious payloads on putdrive.com.(Citation: ESET Telebots Dec 2016)(Citation: ESET Telebots June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d66da21d-1a8c-4b32-b700-f1d3d938b57e`.
