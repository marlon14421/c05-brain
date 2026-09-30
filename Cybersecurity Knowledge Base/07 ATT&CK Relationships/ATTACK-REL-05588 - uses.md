---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0241"
target_object: "T1059.001"
stix_relationship_id: "relationship--ed91791b-8e5a-4e0c-b77c-6fad78be7378"
---
# Relationship 5588: S0241 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0241 - RATANKBA|S0241: RATANKBA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

There is a variant of [RATANKBA](https://attack.mitre.org/software/S0241) that uses a PowerShell script instead of the traditional PE form.(Citation: Lazarus RATANKBA)(Citation: RATANKBA)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ed91791b-8e5a-4e0c-b77c-6fad78be7378`.
