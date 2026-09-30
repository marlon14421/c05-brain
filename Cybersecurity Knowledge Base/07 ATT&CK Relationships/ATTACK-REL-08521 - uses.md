---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0409"
target_object: "T1027.010"
stix_relationship_id: "relationship--fdf56c06-8e42-4cb5-b6e0-a7ec55355ff6"
---
# Relationship 8521: S0409 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0409 - Machete|S0409: Machete]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Machete](https://attack.mitre.org/software/S0409) has used pyobfuscate, zlib compression, and base64 encoding for obfuscation. [Machete](https://attack.mitre.org/groups/G0095) has also used some visual obfuscation techniques by naming variables as combinations of letters to hinder analysis.(Citation: Cylance Machete Mar 2017)(Citation: ESET Machete July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdf56c06-8e42-4cb5-b6e0-a7ec55355ff6`.
