---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0633"
target_object: "T1573.001"
stix_relationship_id: "relationship--b85998e0-9f93-4cb3-a1cf-64e510b109c4"
---
# Relationship 5943: S0633 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0633 - Sliver|S0633: Sliver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sliver](https://attack.mitre.org/software/S0633) can use AES-GCM-256 to encrypt a session key for C2 message exchange.(Citation: GitHub Sliver Encryption)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b85998e0-9f93-4cb3-a1cf-64e510b109c4`.
