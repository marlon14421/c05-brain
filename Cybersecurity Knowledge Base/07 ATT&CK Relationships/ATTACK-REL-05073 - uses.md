---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0012"
target_object: "T1014"
stix_relationship_id: "relationship--f8340d49-ee7a-4ade-988f-3660904a18bb"
---
# Relationship 5073: S0012 — uses → T1014

**Source object:** [[01 ATT&CK/S0012 - PoisonIvy|S0012: PoisonIvy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1014 - Rootkit|T1014: Rootkit]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PoisonIvy](https://attack.mitre.org/software/S0012) starts a rootkit from a malicious file dropped to disk.(Citation: Symantec Darkmoon Aug 2005)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8340d49-ee7a-4ade-988f-3660904a18bb`.
