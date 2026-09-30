---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0034"
target_object: "T1036.004"
stix_relationship_id: "relationship--1747e509-d1d8-4d30-bde5-65adeccb2dae"
---
# Relationship 9762: C0034 — uses → T1036.004

**Source object:** [[01 ATT&CK/C0034 - 2022 Ukraine Electric Power Attack|C0034: 2022 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.004 - Masquerade Task or Service|T1036.004: Masquerade Task or Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2022 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0034), [Sandworm Team](https://attack.mitre.org/groups/G0034) leveraged Systemd service units to masquerade GOGETTER malware as legitimate or seemingly legitimate services.(Citation: Mandiant-Sandworm-Ukraine-2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1747e509-d1d8-4d30-bde5-65adeccb2dae`.
