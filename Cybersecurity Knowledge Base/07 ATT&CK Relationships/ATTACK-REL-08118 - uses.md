---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0470"
target_object: "T1140"
stix_relationship_id: "relationship--7562ef46-c452-4338-9e06-3afdcf2c0e04"
---
# Relationship 8118: S0470 — uses → T1140

**Source object:** [[01 ATT&CK/S0470 - BBK|S0470: BBK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BBK](https://attack.mitre.org/software/S0470) has the ability to decrypt AES encrypted payloads.(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7562ef46-c452-4338-9e06-3afdcf2c0e04`.
