---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0121"
target_object: "T1218.005"
stix_relationship_id: "relationship--0ecbbfa3-6b81-4cf7-9033-373ebbc2832f"
---
# Relationship 5369: G0121 — uses → T1218.005

**Source object:** [[01 ATT&CK/G0121 - Sidewinder|G0121: Sidewinder]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.005 - Mshta|T1218.005: Mshta]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sidewinder](https://attack.mitre.org/groups/G0121) has used mshta.exe to execute malicious payloads.(Citation: Rewterz Sidewinder APT April 2020)(Citation: Rewterz Sidewinder COVID-19 June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ecbbfa3-6b81-4cf7-9033-373ebbc2832f`.
