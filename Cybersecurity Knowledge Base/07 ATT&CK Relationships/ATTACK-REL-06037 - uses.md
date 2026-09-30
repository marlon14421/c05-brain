---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0665"
target_object: "T1027.013"
stix_relationship_id: "relationship--93be81ec-3e56-4257-b869-37bcec2c2625"
---
# Relationship 6037: S0665 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0665 - ThreatNeedle|S0665: ThreatNeedle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThreatNeedle](https://attack.mitre.org/software/S0665) has been compressed and obfuscated using RC4, AES, or XOR.(Citation: Kaspersky ThreatNeedle Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93be81ec-3e56-4257-b869-37bcec2c2625`.
