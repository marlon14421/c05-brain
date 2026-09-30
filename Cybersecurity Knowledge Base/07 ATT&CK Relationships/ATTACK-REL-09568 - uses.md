---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0016"
target_object: "S0052"
stix_relationship_id: "relationship--1593ae11-0bb5-4e16-804a-1383eb0cced5"
---
# Relationship 9568: G0016 — uses → S0052

**Source object:** [[01 ATT&CK/G0016 - APT29|G0016: APT29]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0052 - OnionDuke|S0052: OnionDuke]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

(Citation: F-Secure The Dukes)(Citation: ESET Dukes October 2019)(Citation: Secureworks IRON HEMLOCK Profile)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1593ae11-0bb5-4e16-804a-1383eb0cced5`.
