---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1063"
target_object: "T1482"
stix_relationship_id: "relationship--a4e9aaf6-2c02-45cf-9603-090d65cd8c37"
---
# Relationship 7779: S1063 — uses → T1482

**Source object:** [[01 ATT&CK/S1063 - Brute Ratel C4|S1063: Brute Ratel C4]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Brute Ratel C4](https://attack.mitre.org/software/S1063) can use LDAP queries and `nltest /domain_trusts` for domain trust discovery.(Citation: Palo Alto Brute Ratel July 2022)(Citation: Trend Micro Black Basta October 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a4e9aaf6-2c02-45cf-9603-090d65cd8c37`.
