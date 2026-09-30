---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0062"
target_object: "T1071.001"
stix_relationship_id: "relationship--2892eada-7633-4428-80e0-0e965d5faf5c"
---
# Relationship 8665: S0062 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0062 - DustySky|S0062: DustySky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DustySky](https://attack.mitre.org/software/S0062) has used both HTTP and HTTPS for C2.(Citation: DustySky)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2892eada-7633-4428-80e0-0e965d5faf5c`.
