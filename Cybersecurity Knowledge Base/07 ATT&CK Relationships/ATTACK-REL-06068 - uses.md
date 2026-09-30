---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9027"
target_object: "T1140"
stix_relationship_id: "relationship--3f55cf61-8cbe-48ac-904f-299030d02dc3"
---
# Relationship 6068: S9027 — uses → T1140

**Source object:** [[01 ATT&CK/S9027 - ANELLDR|S9027: ANELLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ANELLDR](https://attack.mitre.org/software/S9027) can decrypt encrypted payload data using AES-256-CBC and subsequently execute the payload in memory.(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f55cf61-8cbe-48ac-904f-299030d02dc3`.
