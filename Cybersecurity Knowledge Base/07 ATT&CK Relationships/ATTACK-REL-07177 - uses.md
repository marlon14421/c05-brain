---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0022"
target_object: "T1018"
stix_relationship_id: "relationship--e7714693-e792-44f0-a224-9899df75fced"
---
# Relationship 7177: G0022 — uses → T1018

**Source object:** [[01 ATT&CK/G0022 - APT3|G0022: APT3]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT3](https://attack.mitre.org/groups/G0022) has a tool that can detect the existence of remote systems.(Citation: Symantec Buckeye)(Citation: FireEye Clandestine Fox)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7714693-e792-44f0-a224-9899df75fced`.
