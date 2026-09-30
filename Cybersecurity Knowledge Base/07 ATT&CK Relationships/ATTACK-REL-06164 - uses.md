---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1573.002"
stix_relationship_id: "relationship--bcb137f0-e92d-47b5-912f-ba8d4f9ff15c"
---
# Relationship 6164: S0251 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) uses SSL and AES ECB for encrypting C2 communications.(Citation: ESET Zebrocy Nov 2018)(Citation: ESET Zebrocy May 2019)(Citation: CISA Zebrocy Oct 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bcb137f0-e92d-47b5-912f-ba8d4f9ff15c`.
