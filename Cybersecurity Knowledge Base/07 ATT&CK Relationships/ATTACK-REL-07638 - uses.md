---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1218"
target_object: "T1505.006"
stix_relationship_id: "relationship--d2a940d8-1976-4b11-9b94-079101e2c0db"
---
# Relationship 7638: S1218 — uses → T1505.006

**Source object:** [[01 ATT&CK/S1218 - VIRTUALPIE|S1218: VIRTUALPIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.006 - vSphere Installation Bundles|T1505.006: vSphere Installation Bundles]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VIRTUALPIE](https://attack.mitre.org/software/S1218) has been installed on VMware ESXi servers through malicious vSphere Installation Bundles (VIBs).(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2a940d8-1976-4b11-9b94-079101e2c0db`.
