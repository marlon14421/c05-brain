---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0180"
target_object: "T1027.013"
stix_relationship_id: "relationship--e5d5ca1f-1e8e-4870-a9ef-33a963ee6148"
---
# Relationship 5380: S0180 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0180 - Volgmer|S0180: Volgmer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [Volgmer](https://attack.mitre.org/software/S0180) variant is encoded using a simple XOR cipher.(Citation: US-CERT Volgmer 2 Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e5d5ca1f-1e8e-4870-a9ef-33a963ee6148`.
