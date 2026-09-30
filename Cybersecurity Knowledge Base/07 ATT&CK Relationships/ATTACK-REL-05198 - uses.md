---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1173"
target_object: "T1071.003"
stix_relationship_id: "relationship--ac296623-0c14-4cb3-b2ce-2fc4a54c64e2"
---
# Relationship 5198: S1173 — uses → T1071.003

**Source object:** [[01 ATT&CK/S1173 - PowerExchange|S1173: PowerExchange]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerExchange](https://attack.mitre.org/software/S1173) can receive and send back the results of executed C2 commands through email.(Citation: Symantec Crambus OCT 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac296623-0c14-4cb3-b2ce-2fc4a54c64e2`.
