---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0263"
target_object: "T1027.013"
stix_relationship_id: "relationship--573e7f53-26e9-4eae-af0e-308d11192f57"
---
# Relationship 6569: S0263 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0263 - TYPEFRAME|S0263: TYPEFRAME]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

APIs and strings in some [TYPEFRAME](https://attack.mitre.org/software/S0263) variants are RC4 encrypted. Another variant is encoded with XOR.(Citation: US-CERT TYPEFRAME June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--573e7f53-26e9-4eae-af0e-308d11192f57`.
