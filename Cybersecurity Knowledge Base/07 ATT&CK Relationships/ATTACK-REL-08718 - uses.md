---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1219"
target_object: "T1573.002"
stix_relationship_id: "relationship--08e8cbfd-7d63-41c0-8440-0be23dc9c6b9"
---
# Relationship 8718: S1219 — uses → T1573.002

**Source object:** [[01 ATT&CK/S1219 - REPTILE|S1219: REPTILE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[REPTILE](https://attack.mitre.org/software/S1219) can use TLS over raw TCP for secure C2.(Citation: Google Cloud Mandiant UNC3886 2024)(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08e8cbfd-7d63-41c0-8440-0be23dc9c6b9`.
