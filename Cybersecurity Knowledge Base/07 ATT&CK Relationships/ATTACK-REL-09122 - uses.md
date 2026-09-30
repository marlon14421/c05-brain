---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0093"
target_object: "T1027.002"
stix_relationship_id: "relationship--5d8315ce-3c76-4b78-8d6a-f0b7b101bcc0"
---
# Relationship 9122: G0093 — uses → T1027.002

**Source object:** [[01 ATT&CK/G0093 - GALLIUM|G0093: GALLIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.002 - Software Packing|T1027.002: Software Packing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GALLIUM](https://attack.mitre.org/groups/G0093) packed some payloads using different types of packers, both known and custom.(Citation: Cybereason Soft Cell June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d8315ce-3c76-4b78-8d6a-f0b7b101bcc0`.
