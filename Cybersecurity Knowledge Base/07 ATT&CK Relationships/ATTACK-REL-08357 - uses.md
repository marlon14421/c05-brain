---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0658"
target_object: "T1027.013"
stix_relationship_id: "relationship--dac0cbc1-227d-41d7-aabf-6c54a009d3c9"
---
# Relationship 8357: S0658 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0658 - XCSSET|S0658: XCSSET]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Older [XCSSET](https://attack.mitre.org/software/S0658) variants use `xxd` to encode modules. Later versions pass an `xxd` or `base64` encoded blob through multiple decoding stages to reconstruct the module name, AppleScript, or shell command. For example, the initial network request uses three layers of hex decoding before executing a curl command in a shell.(Citation: Microsoft March 2025 XCSSET)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dac0cbc1-227d-41d7-aabf-6c54a009d3c9`.
