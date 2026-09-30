---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0236"
target_object: "T1069.001"
stix_relationship_id: "relationship--fb243cd7-7dec-4836-a341-c9e30c0099ee"
---
# Relationship 9516: S0236 — uses → T1069.001

**Source object:** [[01 ATT&CK/S0236 - Kwampirs|S0236: Kwampirs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kwampirs](https://attack.mitre.org/software/S0236) collects a list of users belonging to the local users and administrators groups with the commands net localgroup administrators and net localgroup users .(Citation: Symantec Orangeworm April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb243cd7-7dec-4836-a341-c9e30c0099ee`.
