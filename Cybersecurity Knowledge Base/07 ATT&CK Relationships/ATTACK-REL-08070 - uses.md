---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0347"
target_object: "T1055"
stix_relationship_id: "relationship--4c654359-aefe-4c86-a092-44e99931d340"
---
# Relationship 8070: S0347 — uses → T1055

**Source object:** [[01 ATT&CK/S0347 - AuditCred|S0347: AuditCred]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AuditCred](https://attack.mitre.org/software/S0347) can inject code from files to other running processes.(Citation: TrendMicro Lazarus Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4c654359-aefe-4c86-a092-44e99931d340`.
