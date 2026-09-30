---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0388"
target_object: "T1071.001"
stix_relationship_id: "relationship--78e60e86-72a0-4966-a1b9-19a76102d78f"
---
# Relationship 8613: S0388 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0388 - YAHOYAH|S0388: YAHOYAH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[YAHOYAH](https://attack.mitre.org/software/S0388) uses HTTP for C2.(Citation: TrendMicro TropicTrooper 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--78e60e86-72a0-4966-a1b9-19a76102d78f`.
