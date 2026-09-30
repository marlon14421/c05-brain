---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0129"
target_object: "T1573.001"
stix_relationship_id: "relationship--1ca66056-792e-4e19-8742-a782d87806e4"
---
# Relationship 8038: G0129 — uses → T1573.001

**Source object:** [[01 ATT&CK/G0129 - Mustang Panda|G0129: Mustang Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mustang Panda](https://attack.mitre.org/groups/G0129) has encrypted C2 communications with RC4.(Citation: Eset PlugX Korplug Mustang Panda March 2022)(Citation: Recorded Future REDDELTA July 2020) [Mustang Panda](https://attack.mitre.org/groups/G0129) has also leveraged encryption and compression algorithms to obfuscate the traffic between the system and C2 server, methods observed included RC4, AES, XOR with 0x5a, and LZO.(Citation: Unit42 Bookworm Nov2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ca66056-792e-4e19-8742-a782d87806e4`.
