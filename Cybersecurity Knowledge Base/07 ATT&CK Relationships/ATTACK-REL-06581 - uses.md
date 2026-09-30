---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1027.013"
stix_relationship_id: "relationship--44f1b846-9e75-4f7b-8b6c-a0e68ccbb3ac"
---
# Relationship 6581: G0094 — uses → T1027.013

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has obfuscated code within files by converting hexadecimal strings to decimal numbers using the `CLng function` in combination with processing arithmetic operations and leveraging the `Chr function` to generate readable characters.(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also encoded files with Base64 and RC4.(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has utilized XOR and RC4 to encode malicious payloads.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44f1b846-9e75-4f7b-8b6c-a0e68ccbb3ac`.
