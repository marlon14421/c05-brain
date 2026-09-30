---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0451"
target_object: "T1027.010"
stix_relationship_id: "relationship--14476a38-f67d-45ed-a932-6a9c593e0d61"
---
# Relationship 6501: S0451 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0451 - LoudMiner|S0451: LoudMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoudMiner](https://attack.mitre.org/software/S0451) has obfuscated various scripts.(Citation: ESET LoudMiner June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14476a38-f67d-45ed-a932-6a9c593e0d61`.
