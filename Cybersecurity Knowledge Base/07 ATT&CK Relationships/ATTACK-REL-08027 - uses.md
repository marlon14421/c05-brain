---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0265"
target_object: "T1027"
stix_relationship_id: "relationship--464e688d-b243-4619-a60b-1be6e2d6a827"
---
# Relationship 8027: S0265 — uses → T1027

**Source object:** [[01 ATT&CK/S0265 - Kazuar|S0265: Kazuar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kazuar](https://attack.mitre.org/software/S0265) is obfuscated using the open source ConfuserEx protector. [Kazuar](https://attack.mitre.org/software/S0265) also obfuscates the name of created files/folders/mutexes and encrypts debug messages written to log files using the Rijndael cipher.(Citation: Unit 42 Kazuar May 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--464e688d-b243-4619-a60b-1be6e2d6a827`.
