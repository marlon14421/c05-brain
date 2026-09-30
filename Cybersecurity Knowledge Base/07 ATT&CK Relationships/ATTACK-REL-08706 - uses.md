---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0236"
target_object: "T1027.001"
stix_relationship_id: "relationship--97d77da2-9e26-4168-b14c-9d26093aa5be"
---
# Relationship 8706: S0236 — uses → T1027.001

**Source object:** [[01 ATT&CK/S0236 - Kwampirs|S0236: Kwampirs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.001 - Binary Padding|T1027.001: Binary Padding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Before writing to disk, [Kwampirs](https://attack.mitre.org/software/S0236) inserts a randomly generated string into the middle of the decrypted payload in an attempt to evade hash-based detections.(Citation: Symantec Orangeworm April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97d77da2-9e26-4168-b14c-9d26093aa5be`.
