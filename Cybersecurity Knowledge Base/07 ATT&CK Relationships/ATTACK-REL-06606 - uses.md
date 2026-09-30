---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0687"
target_object: "T1573.002"
stix_relationship_id: "relationship--0766fe91-a8d9-42bd-8023-f2134b280211"
---
# Relationship 6606: S0687 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0687 - Cyclops Blink|S0687: Cyclops Blink]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cyclops Blink](https://attack.mitre.org/software/S0687) can encrypt C2 messages with AES-256-CBC sent underneath TLS. OpenSSL library functions are also used to encrypt each message using a randomly generated key and IV, which are then encrypted using a hard-coded RSA public key.(Citation: NCSC Cyclops Blink February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0766fe91-a8d9-42bd-8023-f2134b280211`.
