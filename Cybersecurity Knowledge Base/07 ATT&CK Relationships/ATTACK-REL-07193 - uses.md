---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1027.002"
stix_relationship_id: "relationship--bf20f37d-ce08-44f1-bc68-f444aabde3c7"
---
# Relationship 7193: G1053 — uses → T1027.002

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has used Themida to pack [Cobalt Strike](https://attack.mitre.org/software/S0154) payloads.(Citation: Google Mandiant Storm-0501 Sabbath Ransomware November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf20f37d-ce08-44f1-bc68-f444aabde3c7`.
