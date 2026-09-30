---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0005"
target_object: "T1568.003"
stix_relationship_id: "relationship--66647c20-2d76-4711-9eee-07d932e75851"
---
# Relationship 9301: G0005 — uses → T1568.003

**Source object:** [[01 ATT&CK/G0005 - APT12|G0005: APT12]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568.003 - DNS Calculation|T1568.003: DNS Calculation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT12](https://attack.mitre.org/groups/G0005) has used multiple variants of [DNS Calculation](https://attack.mitre.org/techniques/T1568/003) including multiplying the first two octets of an IP address and adding the third octet to that value in order to get a resulting command and control port.(Citation: Meyers Numbered Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66647c20-2d76-4711-9eee-07d932e75851`.
