---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0094"
target_object: "T1049"
stix_relationship_id: "relationship--0f6041e9-c2cb-4a22-951d-13587fe4a547"
---
# Relationship 7890: S0094 — uses → T1049

**Source object:** [[01 ATT&CK/S0094 - Trojan.Karagany|S0094: Trojan.Karagany]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Trojan.Karagany](https://attack.mitre.org/software/S0094) can use [netstat](https://attack.mitre.org/software/S0104) to collect a list of network connections.(Citation: Secureworks Karagany July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f6041e9-c2cb-4a22-951d-13587fe4a547`.
