---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1218"
target_object: "T1059.006"
stix_relationship_id: "relationship--0a1f302f-42ae-4947-9b6b-8f89ead35d96"
---
# Relationship 6775: S1218 — uses → T1059.006

**Source object:** [[01 ATT&CK/S1218 - VIRTUALPIE|S1218: VIRTUALPIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.006 - Python|T1059.006: Python]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VIRTUALPIE](https://attack.mitre.org/software/S1218) is a Python-based backdoor malware.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)(Citation: Google Cloud Mandiant UNC3886 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a1f302f-42ae-4947-9b6b-8f89ead35d96`.
