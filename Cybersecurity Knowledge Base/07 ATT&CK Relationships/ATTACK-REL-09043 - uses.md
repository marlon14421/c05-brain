---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1543.001"
stix_relationship_id: "relationship--7596369c-9096-4b91-ab65-574f0bb3d21f"
---
# Relationship 9043: G1052 — uses → T1543.001

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has established persistence using [InvisibleFerret](https://attack.mitre.org/software/S1245) malware to create file to run the script on Startup via LaunchAgents.(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024) [Contagious Interview](https://attack.mitre.org/groups/G1052) has also utilized a plist file located in `/Library/LaunchAgents` to enable a malicious bash script the ability to persist.(Citation: Sekoia ClickFake 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7596369c-9096-4b91-ab65-574f0bb3d21f`.
