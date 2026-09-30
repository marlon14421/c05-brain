---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1588.002"
stix_relationship_id: "relationship--6ef45519-7ca1-44a4-8421-152af4e85d68"
---
# Relationship 7180: G1057 — uses → T1588.002

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has obtained MeshCentral to deploy agents masquerading as legitimate cloud endpoints.(Citation: Google_SHOracle_Jun2026) [ShinyHunters](https://attack.mitre.org/groups/G1057) has obtained WinSCP to gather information on S3 bucket configurations.(Citation: Unit42KelleyVaya_BlingLibra_Aug2024) [ShinyHunters](https://attack.mitre.org/groups/G1057) has obtained [ConnectWise](https://attack.mitre.org/software/S0591) and other RMM tools to gain initial access.(Citation: ElecticIQ Buyukkaya_ShinyHunters_Sept2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6ef45519-7ca1-44a4-8421-152af4e85d68`.
