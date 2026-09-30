---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0004"
target_object: "T1569.002"
stix_relationship_id: "relationship--8bfa94cf-4eeb-442c-8f18-25b07cd3cbf5"
---
# Relationship 6769: G0004 — uses → T1569.002

**Source object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ke3chang](https://attack.mitre.org/groups/G0004) has used a tool known as RemoteExec (similar to [PsExec](https://attack.mitre.org/software/S0029)) to remotely execute batch scripts and binaries.(Citation: NCC Group APT15 Alive and Strong)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8bfa94cf-4eeb-442c-8f18-25b07cd3cbf5`.
