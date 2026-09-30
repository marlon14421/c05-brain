---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1110"
target_object: "T1573.001"
stix_relationship_id: "relationship--a8822aba-51e7-44de-91f0-24e84390ee7c"
---
# Relationship 7276: S1110 — uses → T1573.001

**Source object:** [[01 ATT&CK/S1110 - SLIGHTPULSE|S1110: SLIGHTPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SLIGHTPULSE](https://attack.mitre.org/software/S1110) can RC4 encrypt all incoming and outgoing C2 messages.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8822aba-51e7-44de-91f0-24e84390ee7c`.
