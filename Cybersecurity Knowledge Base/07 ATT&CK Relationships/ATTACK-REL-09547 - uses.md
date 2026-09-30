---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0398"
target_object: "T1140"
stix_relationship_id: "relationship--6cb89bfe-73f6-47d8-beb5-f8b2d66e0bfd"
---
# Relationship 9547: S0398 — uses → T1140

**Source object:** [[01 ATT&CK/S0398 - HyperBro|S0398: HyperBro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HyperBro](https://attack.mitre.org/software/S0398) can unpack and decrypt its payload prior to execution.(Citation: Trend Micro DRBControl February 2020)(Citation: Trend Micro Iron Tiger April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cb89bfe-73f6-47d8-beb5-f8b2d66e0bfd`.
