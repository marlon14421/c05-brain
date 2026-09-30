---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1155"
target_object: "T1082"
stix_relationship_id: "relationship--698c4736-5a86-4d72-9855-4bdee856d6de"
---
# Relationship 8155: S1155 — uses → T1082

**Source object:** [[01 ATT&CK/S1155 - Covenant|S1155: Covenant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Covenant](https://attack.mitre.org/software/S1155) implants can gather basic information on infected systems.(Citation: Github Covenant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--698c4736-5a86-4d72-9855-4bdee856d6de`.
