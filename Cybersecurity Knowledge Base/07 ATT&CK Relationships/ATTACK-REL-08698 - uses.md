---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1074.001"
stix_relationship_id: "relationship--66773d13-7e97-493f-a1b6-9484c52cc6a1"
---
# Relationship 8698: S9010 — uses → T1074.001

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has staged collected data in a working directory within a temp folder to include `/tmp/ijewf`.(Citation: Koi Glassworm New Tricks December 2025)(Citation: Socket GlassWorm January 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--66773d13-7e97-493f-a1b6-9484c52cc6a1`.
