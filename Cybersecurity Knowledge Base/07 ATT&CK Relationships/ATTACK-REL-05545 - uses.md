---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0603"
target_object: "T1134.001"
stix_relationship_id: "relationship--3ee76373-418f-43af-adb5-3c0fcb7f080e"
---
# Relationship 5545: S0603 — uses → T1134.001

**Source object:** [[01 ATT&CK/S0603 - Stuxnet|S0603: Stuxnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.001 - Token Impersonation-Theft|T1134.001: Token Impersonation/Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Stuxnet](https://attack.mitre.org/software/S0603) attempts to impersonate an anonymous token to enumerate bindings in the service control manager.(Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ee76373-418f-43af-adb5-3c0fcb7f080e`.
