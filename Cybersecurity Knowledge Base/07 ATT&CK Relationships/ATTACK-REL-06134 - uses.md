---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1218"
target_object: "T1570"
stix_relationship_id: "relationship--c29d57a2-ebda-40eb-9023-361e6a89610a"
---
# Relationship 6134: S1218 — uses → T1570

**Source object:** [[01 ATT&CK/S1218 - VIRTUALPIE|S1218: VIRTUALPIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VIRTUALPIE](https://attack.mitre.org/software/S1218) has file transfer capabilities.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c29d57a2-ebda-40eb-9023-361e6a89610a`.
