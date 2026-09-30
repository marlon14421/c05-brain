---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0239"
target_object: "T1012"
stix_relationship_id: "relationship--77d079b6-2df9-4ae9-bc7c-1ebe99708660"
---
# Relationship 8208: S0239 — uses → T1012

**Source object:** [[01 ATT&CK/S0239 - Bankshot|S0239: Bankshot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bankshot](https://attack.mitre.org/software/S0239) searches for certain Registry keys to be configured before executing the payload.(Citation: US-CERT Bankshot Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--77d079b6-2df9-4ae9-bc7c-1ebe99708660`.
