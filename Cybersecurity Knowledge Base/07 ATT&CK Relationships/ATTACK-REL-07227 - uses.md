---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0347"
target_object: "T1027.013"
stix_relationship_id: "relationship--f9a34eaa-c17c-400a-b4e0-063445e430af"
---
# Relationship 7227: S0347 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0347 - AuditCred|S0347: AuditCred]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AuditCred](https://attack.mitre.org/software/S0347) encrypts the configuration.(Citation: TrendMicro Lazarus Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f9a34eaa-c17c-400a-b4e0-063445e430af`.
