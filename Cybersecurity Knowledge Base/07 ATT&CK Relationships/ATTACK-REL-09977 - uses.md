---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0082"
target_object: "T1007"
stix_relationship_id: "relationship--bae7f2fb-99d8-4acf-b61e-f37a215aa82e"
---
# Relationship 9977: S0082 — uses → T1007

**Source object:** [[01 ATT&CK/S0082 - Emissary|S0082: Emissary]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Emissary](https://attack.mitre.org/software/S0082) has the capability to execute the command net start to interact with services.(Citation: Emissary Trojan Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bae7f2fb-99d8-4acf-b61e-f37a215aa82e`.
