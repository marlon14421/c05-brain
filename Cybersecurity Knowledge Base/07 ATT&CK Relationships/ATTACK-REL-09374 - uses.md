---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0018"
target_object: "T1573.002"
stix_relationship_id: "relationship--10c33088-630e-456d-ad0f-8a63be4d3946"
---
# Relationship 9374: S0018 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0018 - Sykipot|S0018: Sykipot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sykipot](https://attack.mitre.org/software/S0018) uses SSL for encrypting C2 communications.(Citation: Blasco 2013)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--10c33088-630e-456d-ad0f-8a63be4d3946`.
