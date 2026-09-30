---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0532"
target_object: "T1021.002"
stix_relationship_id: "relationship--ef5479d8-f8f3-4754-989e-9930a245899c"
---
# Relationship 6454: S0532 — uses → T1021.002

**Source object:** [[01 ATT&CK/S0532 - Lucifer|S0532: Lucifer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lucifer](https://attack.mitre.org/software/S0532) can infect victims by brute forcing SMB.(Citation: Unit 42 Lucifer June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ef5479d8-f8f3-4754-989e-9930a245899c`.
