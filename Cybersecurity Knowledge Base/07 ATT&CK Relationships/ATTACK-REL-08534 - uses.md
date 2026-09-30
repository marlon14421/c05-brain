---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0637"
target_object: "T1204.002"
stix_relationship_id: "relationship--19ca041f-64be-42f8-9ed1-361410a4c28b"
---
# Relationship 8534: S0637 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0637 - NativeZone|S0637: NativeZone]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NativeZone](https://attack.mitre.org/software/S0637) can display an RTF document to the user to enable execution of [Cobalt Strike](https://attack.mitre.org/software/S0154) stage shellcode.(Citation: MSTIC Nobelium Toolset May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--19ca041f-64be-42f8-9ed1-361410a4c28b`.
