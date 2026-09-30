---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1505.003"
stix_relationship_id: "relationship--2dbed740-1b50-4d59-a729-a1d9e6a839df"
---
# Relationship 5001: G0049 — uses → T1505.003

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has used web shells, often to maintain access to a victim network.(Citation: Unit42 OilRig Playbook 2023)(Citation: FireEye APT34 Webinar Dec 2017)(Citation: Crowdstrike GTR2020 Mar 2020)(Citation: Trend Micro Earth Simnavaz October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2dbed740-1b50-4d59-a729-a1d9e6a839df`.
