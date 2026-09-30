---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0065"
target_object: "T1059.003"
stix_relationship_id: "relationship--43a63e7a-d673-47c0-9af5-76dcd5a5d9b8"
---
# Relationship 9970: S0065 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0065 - 4H RAT|S0065: 4H RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[4H RAT](https://attack.mitre.org/software/S0065) has the capability to create a remote shell.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43a63e7a-d673-47c0-9af5-76dcd5a5d9b8`.
