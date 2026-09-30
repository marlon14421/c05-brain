---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0059"
target_object: "T1021.001"
stix_relationship_id: "relationship--43c20c81-984f-418a-9202-252a3afbec46"
---
# Relationship 8995: G0059 — uses → T1021.001

**Source object:** [[01 ATT&CK/G0059 - Magic Hound|G0059: Magic Hound]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.001 - Remote Desktop Protocol|T1021.001: Remote Desktop Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Magic Hound](https://attack.mitre.org/groups/G0059) has used Remote Desktop Services to copy tools on targeted systems.(Citation: DFIR Report APT35 ProxyShell March 2022)(Citation: DFIR Phosphorus November 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43c20c81-984f-418a-9202-252a3afbec46`.
