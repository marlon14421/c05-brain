---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1548"
stix_relationship_id: "relationship--650b58f8-3968-420f-94c2-6173fbc600c6"
---
# Relationship 6684: G1048 — uses → T1548

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1548 - Abuse Elevation Control Mechanism|T1548: Abuse Elevation Control Mechanism]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has used vSphere Installation Bundles (VIBs) that contained modified descriptor XML files with the `acceptance-level` set to `partner` which allowed for privilege escalation.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--650b58f8-3968-420f-94c2-6173fbc600c6`.
