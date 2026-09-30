---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9027"
target_object: "T1027.016"
stix_relationship_id: "relationship--b219dd79-cc7d-4119-a5e9-80b3703730f2"
---
# Relationship 5992: S9027 — uses → T1027.016

**Source object:** [[01 ATT&CK/S9027 - ANELLDR|S9027: ANELLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.016 - Junk Code Insertion|T1027.016: Junk Code Insertion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ANELLDR](https://attack.mitre.org/software/S9027) can use junk code for payload obfuscation.(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b219dd79-cc7d-4119-a5e9-80b3703730f2`.
