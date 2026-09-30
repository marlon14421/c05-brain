---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1071.001"
stix_relationship_id: "relationship--166326b3-6864-4667-aee9-4d7b24cc75d8"
---
# Relationship 8741: G0049 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has used HTTP for C2.(Citation: Unit42 OilRig Playbook 2023)(Citation: FireEye APT34 Webinar Dec 2017)(Citation: FireEye APT34 July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--166326b3-6864-4667-aee9-4d7b24cc75d8`.
