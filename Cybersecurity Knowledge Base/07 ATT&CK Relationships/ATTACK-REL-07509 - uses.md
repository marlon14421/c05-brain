---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0082"
target_object: "T1082"
stix_relationship_id: "relationship--4a959425-4d43-4969-9a47-768894a3afaa"
---
# Relationship 7509: S0082 — uses → T1082

**Source object:** [[01 ATT&CK/S0082 - Emissary|S0082: Emissary]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Emissary](https://attack.mitre.org/software/S0082) has the capability to execute ver and systeminfo commands.(Citation: Emissary Trojan Feb 2016)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a959425-4d43-4969-9a47-768894a3afaa`.
