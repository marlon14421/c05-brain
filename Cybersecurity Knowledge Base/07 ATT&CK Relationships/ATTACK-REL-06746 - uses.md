---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0017"
target_object: "T1573.002"
stix_relationship_id: "relationship--e54282cb-8567-4c43-b6ab-3cfd0e52fb9a"
---
# Relationship 6746: S0017 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0017 - BISCUIT|S0017: BISCUIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BISCUIT](https://attack.mitre.org/software/S0017) uses SSL for encrypting C2 communications.(Citation: Mandiant APT1 Appendix)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e54282cb-8567-4c43-b6ab-3cfd0e52fb9a`.
