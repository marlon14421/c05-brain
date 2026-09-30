---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0366"
target_object: "T1573.002"
stix_relationship_id: "relationship--d9bfa498-69a1-44f9-8e44-67a6a4c48088"
---
# Relationship 9995: S0366 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0366 - WannaCry|S0366: WannaCry]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WannaCry](https://attack.mitre.org/software/S0366) uses [Tor](https://attack.mitre.org/software/S0183) for command and control traffic and routes a custom cryptographic protocol over the [Tor](https://attack.mitre.org/software/S0183) circuit.(Citation: SecureWorks WannaCry Analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9bfa498-69a1-44f9-8e44-67a6a4c48088`.
