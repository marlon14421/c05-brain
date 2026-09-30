---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0396"
target_object: "T1518.001"
stix_relationship_id: "relationship--e900ada7-1b3a-442d-aa86-5cd16a3a2c00"
---
# Relationship 8755: S0396 — uses → T1518.001

**Source object:** [[01 ATT&CK/S0396 - EvilBunny|S0396: EvilBunny]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EvilBunny](https://attack.mitre.org/software/S0396) has been observed querying installed antivirus software.(Citation: Cyphort EvilBunny Dec 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e900ada7-1b3a-442d-aa86-5cd16a3a2c00`.
