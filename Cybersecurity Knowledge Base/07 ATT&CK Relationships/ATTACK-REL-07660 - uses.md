---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0206"
target_object: "T1055"
stix_relationship_id: "relationship--66f859b2-4bc2-4520-afd4-8f8a7b71a50c"
---
# Relationship 7660: S0206 — uses → T1055

**Source object:** [[01 ATT&CK/S0206 - Wiarp|S0206: Wiarp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wiarp](https://attack.mitre.org/software/S0206) creates a backdoor through which remote attackers can inject files into running processes.(Citation: Symantec Wiarp May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66f859b2-4bc2-4520-afd4-8f8a7b71a50c`.
