---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1505.006"
stix_relationship_id: "relationship--9df873c3-9820-4b94-adae-b6a5cd271dce"
---
# Relationship 7625: G1048 — uses → T1505.006

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.006 - vSphere Installation Bundles|T1505.006: vSphere Installation Bundles]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has used vSphere Installation Bundles (VIBs) to install malware and establish persistence across ESXi hypervisors.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)(Citation: Google Cloud Threat Intelligence VMWare ESXi Zero-Day 2023)(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9df873c3-9820-4b94-adae-b6a5cd271dce`.
