---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9001"
target_object: "T1001"
stix_relationship_id: "relationship--4802a823-0a51-47c2-aabe-369a2430ba95"
---
# Relationship 6607: S9001 — uses → T1001

**Source object:** [[01 ATT&CK/S9001 - SystemBC|S9001: SystemBC]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001 - Data Obfuscation|T1001: Data Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SystemBC](https://attack.mitre.org/software/S9001) has encoded with XOR and encrypted with RC4 its beacon.(Citation: Lumen_SystemBC_Sept2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4802a823-0a51-47c2-aabe-369a2430ba95`.
