---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0002"
target_object: "T1071.001"
stix_relationship_id: "relationship--7ac258e9-acfa-4bc4-a676-201cf40be956"
---
# Relationship 6263: C0002 — uses → T1071.001

**Source object:** [[01 ATT&CK/C0002 - Night Dragon|C0002: Night Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Night Dragon](https://attack.mitre.org/campaigns/C0002), threat actors used HTTP for C2.(Citation: McAfee Night Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ac258e9-acfa-4bc4-a676-201cf40be956`.
