---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1027.013"
stix_relationship_id: "relationship--ae6af46e-ac3d-40dd-8733-0f5f8429b5ef"
---
# Relationship 6338: S9043 — uses → T1027.013

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has used a hybrid AES-256-GCM and RSA OAEP-SHA256 encryption to archive gathered data. [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has also utilized custom MD5-keystream XOR cipher to encrypt data.(Citation: Trend Micro TeamPCP MAY 2026) [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has also been deployed via an obfuscated script using Bun JavaScript runtime.(Citation: Flashpoint Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae6af46e-ac3d-40dd-8733-0f5f8429b5ef`.
