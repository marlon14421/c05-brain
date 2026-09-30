---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0275"
target_object: "T1573.001"
stix_relationship_id: "relationship--64eefbfb-5241-4325-919d-4739504644c2"
---
# Relationship 9465: S0275 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0275 - UPPERCUT|S0275: UPPERCUT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some versions of [UPPERCUT](https://attack.mitre.org/software/S0275) have used the hard-coded string “this is the encrypt key” for Blowfish encryption when communicating with a C2. Later versions have hard-coded keys uniquely for each C2 address.(Citation: FireEye APT10 Sept 2018) [UPPERCUT](https://attack.mitre.org/software/S0275) has also used custom ChaCha20, XOR, and LZO algorithms for C2 communication.(Citation: Trend Micro Earth Kasha Updates APR 2025)(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--64eefbfb-5241-4325-919d-4739504644c2`.
