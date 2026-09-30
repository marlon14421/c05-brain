---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1598.003"
stix_relationship_id: "relationship--9aa9b9f6-a22f-4763-a2ff-7635f5022727"
---
# Relationship 6493: G0007 — uses → T1598.003

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1598.003 - Spearphishing Link|T1598.003: Spearphishing Link]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has conducted credential phishing campaigns with links that redirect to credential harvesting sites.(Citation: Google TAG Ukraine Threat Landscape March 2022)(Citation: DOJ GRU Indictment Jul 2018)(Citation: ESET Zebrocy May 2019)(Citation: US District Court Indictment GRU Oct 2018)(Citation: Secureworks IRON TWILIGHT Active Measures March 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9aa9b9f6-a22f-4763-a2ff-7635f5022727`.
