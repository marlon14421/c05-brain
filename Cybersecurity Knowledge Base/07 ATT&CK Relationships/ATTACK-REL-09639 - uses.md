---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1518.001"
stix_relationship_id: "relationship--085c21c0-4afb-4df2-bf86-803457be16fd"
---
# Relationship 9639: S1228 — uses → T1518.001

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518.001 - Security Software Discovery|T1518.001: Security Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has identified AV products on an infected host using the following command: `WMIC /Node:localhost /Namespace:\\root\SecurityCenter2 Path AntiVirusProduct Get displayName /Format:List`.(Citation: Trend Micro MUSTANG PANDA PUBLOAD HIUPAN SEPTEMBER 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--085c21c0-4afb-4df2-bf86-803457be16fd`.
