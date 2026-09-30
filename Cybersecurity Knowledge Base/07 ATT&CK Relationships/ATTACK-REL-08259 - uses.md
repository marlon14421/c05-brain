---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1212"
target_object: "T1090"
stix_relationship_id: "relationship--12c19ecc-2d25-45c6-b13b-439220248d4e"
---
# Relationship 8259: S1212 — uses → T1090

**Source object:** [[01 ATT&CK/S1212 - RansomHub|S1212: RansomHub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RansomHub](https://attack.mitre.org/software/S1212) can use a proxy to connect to remote SFTP servers.(Citation: Group-IB RansomHub FEB 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12c19ecc-2d25-45c6-b13b-439220248d4e`.
