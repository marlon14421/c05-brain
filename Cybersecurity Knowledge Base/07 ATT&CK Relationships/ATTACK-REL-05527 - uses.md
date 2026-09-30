---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1226"
target_object: "T1070.006"
stix_relationship_id: "relationship--e7133f0c-0e76-4a10-8aa4-05a38fc1fbf7"
---
# Relationship 5527: S1226 — uses → T1070.006

**Source object:** [[01 ATT&CK/S1226 - BOOKWORM|S1226: BOOKWORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOOKWORM](https://attack.mitre.org/software/S1226) has modified file timestamps from the export address table (EAT) to make it difficult to discern when the module was created. (Citation: Palo Alto Networks, Unit 42)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e7133f0c-0e76-4a10-8aa4-05a38fc1fbf7`.
