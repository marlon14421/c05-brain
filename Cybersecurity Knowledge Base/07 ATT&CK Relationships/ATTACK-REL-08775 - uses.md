---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0084"
target_object: "T1074.001"
stix_relationship_id: "relationship--e08fbaf9-0efe-41b1-99f7-ec61f38b175c"
---
# Relationship 8775: S0084 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0084 - Mis-Type|S0084: Mis-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mis-Type](https://attack.mitre.org/software/S0084) has temporarily stored collected information to the files `“%AppData%\{Unique Identifier}\HOSTRURKLSR”` and `“%AppData%\{Unique Identifier}\NEWERSSEMP”`.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e08fbaf9-0efe-41b1-99f7-ec61f38b175c`.
