---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0606"
target_object: "T1057"
stix_relationship_id: "relationship--70b27780-b19a-4313-88ea-1038ce0fc386"
---
# Relationship 9833: S0606 — uses → T1057

**Source object:** [[01 ATT&CK/S0606 - Bad Rabbit|S0606: Bad Rabbit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bad Rabbit](https://attack.mitre.org/software/S0606) can enumerate all running processes to compare hashes.(Citation: Secure List Bad Rabbit)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70b27780-b19a-4313-88ea-1038ce0fc386`.
