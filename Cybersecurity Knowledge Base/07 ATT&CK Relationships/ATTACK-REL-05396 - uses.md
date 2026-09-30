---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0374"
target_object: "T1059.006"
stix_relationship_id: "relationship--2209a958-9359-4866-80e9-80d0cc660868"
---
# Relationship 5396: S0374 — uses → T1059.006

**Source object:** [[01 ATT&CK/S0374 - SpeakUp|S0374: SpeakUp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SpeakUp](https://attack.mitre.org/software/S0374) uses Python scripts.(Citation: CheckPoint SpeakUp Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2209a958-9359-4866-80e9-80d0cc660868`.
