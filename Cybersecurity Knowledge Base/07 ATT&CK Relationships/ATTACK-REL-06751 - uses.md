---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1485"
stix_relationship_id: "relationship--3184811d-4b00-4fdd-aa4b-5c16eb3294ed"
---
# Relationship 6751: S9008 — uses → T1485

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has destroyed the victim’s home directory by overwriting and deleting every writable file within the user's home folder.(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Socket Shai-Hulud November 2025) [Shai-Hulud](https://attack.mitre.org/software/S9008) has also utilized the `shred` command on Linux devices.(Citation: Microsoft Shai-Hulud December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3184811d-4b00-4fdd-aa4b-5c16eb3294ed`.
