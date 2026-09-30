---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0387"
target_object: "T1070.006"
stix_relationship_id: "relationship--8343b346-e529-4f28-a569-ae5f9a862ddf"
---
# Relationship 5472: S0387 — uses → T1070.006

**Source object:** [[01 ATT&CK/S0387 - KeyBoy|S0387: KeyBoy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KeyBoy](https://attack.mitre.org/software/S0387) time-stomped its DLL in order to evade detection.(Citation: PWC KeyBoys Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8343b346-e529-4f28-a569-ae5f9a862ddf`.
