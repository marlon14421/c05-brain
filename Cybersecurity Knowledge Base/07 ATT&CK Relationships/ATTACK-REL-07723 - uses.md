---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1113"
stix_relationship_id: "relationship--48f662fe-1ba2-4c19-b782-dd06d9fb67fa"
---
# Relationship 7723: G0007 — uses → T1113

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used tools to take screenshots from victims.(Citation: ESET Sednit Part 2)(Citation: XAgentOSX 2017)(Citation: DOJ GRU Indictment Jul 2018)(Citation: Secureworks IRON TWILIGHT Active Measures March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48f662fe-1ba2-4c19-b782-dd06d9fb67fa`.
