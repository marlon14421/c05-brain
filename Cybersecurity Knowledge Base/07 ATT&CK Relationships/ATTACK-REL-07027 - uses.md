---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1063"
target_object: "T1087.002"
stix_relationship_id: "relationship--959c7695-01a5-4be1-9951-799749796cf4"
---
# Relationship 7027: S1063 — uses → T1087.002

**Source object:** [[01 ATT&CK/S1063 - Brute Ratel C4|S1063: Brute Ratel C4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Brute Ratel C4](https://attack.mitre.org/software/S1063) can use LDAP queries, `net group "Domain Admins" /domain` and `net user /domain` for discovery.(Citation: Palo Alto Brute Ratel July 2022)(Citation: Trend Micro Black Basta October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--959c7695-01a5-4be1-9951-799749796cf4`.
