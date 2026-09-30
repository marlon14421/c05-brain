---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0037"
target_object: "T1059"
stix_relationship_id: "relationship--1f764874-0e08-4799-9487-a9e12c499c13"
---
# Relationship 6991: G0037 — uses → T1059

**Source object:** [[01 ATT&CK/G0037 - FIN6|G0037: FIN6]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059 - Command and Scripting Interpreter|T1059: Command and Scripting Interpreter]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN6](https://attack.mitre.org/groups/G0037) has used scripting to iterate through a list of compromised PoS systems, copy data to a log file, and remove the original data files.(Citation: FireEye FIN6 April 2016)(Citation: FireEye FIN6 Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f764874-0e08-4799-9487-a9e12c499c13`.
