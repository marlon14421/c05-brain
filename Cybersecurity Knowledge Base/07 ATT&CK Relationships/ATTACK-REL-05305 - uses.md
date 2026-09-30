---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1044"
target_object: "T1560.003"
stix_relationship_id: "relationship--d29ff57c-2821-45e9-94b5-beb62f63f8ea"
---
# Relationship 5305: S1044 — uses → T1560.003

**Source object:** [[01 ATT&CK/S1044 - FunnyDream|S1044: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FunnyDream](https://attack.mitre.org/software/S1044) has compressed collected files with zLib and encrypted them using an XOR operation with the string key from the command line or `qwerasdf` if the command line argument doesn’t contain the key. File names are obfuscated using XOR with the same key as the compressed file content.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d29ff57c-2821-45e9-94b5-beb62f63f8ea`.
