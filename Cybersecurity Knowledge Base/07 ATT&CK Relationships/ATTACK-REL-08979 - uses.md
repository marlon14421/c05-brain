---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1570"
stix_relationship_id: "relationship--c2d06b1b-823c-4f94-9b11-79892bca9f4e"
---
# Relationship 8979: G0034 — uses → T1570

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1570 - Lateral Tool Transfer|T1570: Lateral Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has used `move` to transfer files to a network share and has copied payloads--such as [Prestige](https://attack.mitre.org/software/S1058) ransomware--to an Active Directory Domain Controller and distributed via the Default Domain Group Policy Object.(Citation: Dragos Crashoverride 2018)(Citation: Microsoft Prestige ransomware October 2022) Additionally, [Sandworm Team](https://attack.mitre.org/groups/G0034) has transferred an ISO file into the OT network to gain initial access.(Citation: Mandiant-Sandworm-Ukraine-2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2d06b1b-823c-4f94-9b11-79892bca9f4e`.
