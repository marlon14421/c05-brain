---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0139"
target_object: "T1496.001"
stix_relationship_id: "relationship--8f4e363a-ce2b-4a36-92fb-791d8ffc30d5"
---
# Relationship 5581: G0139 — uses → T1496.001

**Source object:** [[01 ATT&CK/G0139 - TeamTNT|G0139: TeamTNT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1496.001 - Compute Hijacking|T1496.001: Compute Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TeamTNT](https://attack.mitre.org/groups/G0139) has deployed XMRig Docker images to mine cryptocurrency.(Citation: Lacework TeamTNT May 2021)(Citation: Cado Security TeamTNT Worm August 2020) [TeamTNT](https://attack.mitre.org/groups/G0139) has also infected Docker containers and Kubernetes clusters with XMRig, and used RainbowMiner and lolMiner for mining cryptocurrency.(Citation: Cisco Talos Intelligence Group)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f4e363a-ce2b-4a36-92fb-791d8ffc30d5`.
