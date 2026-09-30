---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0515"
target_object: "T1573.002"
stix_relationship_id: "relationship--ea8e9109-739f-485c-8d13-fb5ed6b2fdcd"
---
# Relationship 5102: S0515 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0515 - WellMail|S0515: WellMail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WellMail](https://attack.mitre.org/software/S0515) can use hard coded client and certificate authority certificates to communicate with C2 over mutual TLS.(Citation: CISA WellMail July 2020)(Citation: NCSC APT29 July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ea8e9109-739f-485c-8d13-fb5ed6b2fdcd`.
