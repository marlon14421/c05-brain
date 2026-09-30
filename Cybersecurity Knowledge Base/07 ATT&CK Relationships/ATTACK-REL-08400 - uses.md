---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "T1012"
stix_relationship_id: "relationship--feef4e0f-c65b-42ed-9fdf-e5fe38a6adaa"
---
# Relationship 8400: G0030 — uses → T1012

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has run commands such as `reg query HKLM\SYSTEM\CurrentControlSet\Services\[service name]\Parameters` to verify if installed implants are running as a service.(Citation: Cisco LotusBlossom 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--feef4e0f-c65b-42ed-9fdf-e5fe38a6adaa`.
