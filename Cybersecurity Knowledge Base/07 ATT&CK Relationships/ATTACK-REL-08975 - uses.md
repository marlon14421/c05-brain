---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1213.006"
stix_relationship_id: "relationship--106a3217-411d-4927-9023-b14750dc3fc3"
---
# Relationship 8975: S9041 — uses → T1213.006

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1213.006 - Databases|T1213.006: Databases]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) can extract credentials from multiple database configuration files including ~/.pgpass, ~/.my.cnf, ~/.mongorc.js, and /etc/mysql/my.cnf.(Citation: Aqua Security Blog Trivy Compromise APR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--106a3217-411d-4927-9023-b14750dc3fc3`.
