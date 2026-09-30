---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1205"
stix_relationship_id: "relationship--cc0c7d4b-eebb-4e95-9e03-972b1e943208"
---
# Relationship 6667: S1228 — uses → T1205

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has utilized a magic value in C2 communications and only executes in memory when response packets match specific values of 17 03 03.(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)(Citation: IBM MUSTANG PANDA PUBLOAD CLAIMLOADER JUNE 2025)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)(Citation: PaloAlto MUSTANG PANDA PUBLOAD MARCH 2024) [PUBLOAD](https://attack.mitre.org/software/S1228) has also used magic bytes consisting of 46 77 4d.(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cc0c7d4b-eebb-4e95-9e03-972b1e943208`.
