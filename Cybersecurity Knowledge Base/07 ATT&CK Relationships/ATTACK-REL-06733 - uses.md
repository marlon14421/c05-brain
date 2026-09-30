---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0125"
target_object: "T1071.003"
stix_relationship_id: "relationship--560a7947-3823-4f2b-8b84-238f9a9a2552"
---
# Relationship 6733: S0125 — uses → T1071.003

**Source object:** [[01 ATT&CK/S0125 - Remsec|S0125: Remsec]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remsec](https://attack.mitre.org/software/S0125) is capable of using SMTP for C2.(Citation: Symantec Remsec IOCs)(Citation: Kaspersky ProjectSauron Full Report)(Citation: Kaspersky ProjectSauron Technical Analysis)(Citation: Threatpost Sauron)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--560a7947-3823-4f2b-8b84-238f9a9a2552`.
