---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0060"
target_object: "T1573.001"
stix_relationship_id: "relationship--ec4d07a2-8c8b-4df8-bb9e-b8c3e23d8dc5"
---
# Relationship 8061: G0060 — uses → T1573.001

**Source object:** [[01 ATT&CK/G0060 - BRONZE BUTLER|G0060: BRONZE BUTLER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRONZE BUTLER](https://attack.mitre.org/groups/G0060) has used RC4 encryption (for Datper malware) and AES (for xxmm malware) to obfuscate HTTP traffic. [BRONZE BUTLER](https://attack.mitre.org/groups/G0060) has also used a tool called RarStar that encodes data with a custom XOR algorithm when posting it to a C2 server.(Citation: Secureworks BRONZE BUTLER Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec4d07a2-8c8b-4df8-bb9e-b8c3e23d8dc5`.
