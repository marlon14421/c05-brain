---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0034"
target_object: "T1505.003"
stix_relationship_id: "relationship--4e1b8403-d2ed-4d24-b7cd-2974ef9ba1d3"
---
# Relationship 9561: C0034 — uses → T1505.003

**Source object:** [[01 ATT&CK/C0034 - 2022 Ukraine Electric Power Attack|C0034: 2022 Ukraine Electric Power Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2022 Ukraine Electric Power Attack](https://attack.mitre.org/campaigns/C0034), [Sandworm Team](https://attack.mitre.org/groups/G0034) deployed the Neo-REGEORG webshell on an internet-facing server.(Citation: Mandiant-Sandworm-Ukraine-2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e1b8403-d2ed-4d24-b7cd-2974ef9ba1d3`.
