---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0519"
target_object: "T1601.001"
stix_relationship_id: "relationship--1fbc7b2a-1cdb-455b-bd5a-b0ff29efe800"
---
# Relationship 7073: S0519 — uses → T1601.001

**Source object:** [[01 ATT&CK/S0519 - SYNful Knock|S0519: SYNful Knock]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1601.001 - Patch System Image|T1601.001: Patch System Image]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SYNful Knock](https://attack.mitre.org/software/S0519) is malware that is inserted into a network device by patching the operating system image.(Citation: Mandiant - Synful Knock)(Citation: Cisco Synful Knock Evolution)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1fbc7b2a-1cdb-455b-bd5a-b0ff29efe800`.
