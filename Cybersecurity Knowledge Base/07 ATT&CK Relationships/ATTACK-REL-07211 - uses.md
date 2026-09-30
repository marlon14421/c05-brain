---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1025"
target_object: "T1553.005"
stix_relationship_id: "relationship--7a402933-faba-4de0-a7a5-3b44761cc062"
---
# Relationship 7211: S1025 — uses → T1553.005

**Source object:** [[01 ATT&CK/S1025 - Amadey|S1025: Amadey]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.005 - Mark-of-the-Web Bypass|T1553.005: Mark-of-the-Web Bypass]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Amadey](https://attack.mitre.org/software/S1025) has modified the `:Zone.Identifier` in the ADS area to zero.(Citation: Korean FSI TA505 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a402933-faba-4de0-a7a5-3b44761cc062`.
