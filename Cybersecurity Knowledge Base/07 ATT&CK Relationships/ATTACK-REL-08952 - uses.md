---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0376"
target_object: "T1008"
stix_relationship_id: "relationship--1708aa35-a362-429f-be06-82dc106dfeb4"
---
# Relationship 8952: S0376 — uses → T1008

**Source object:** [[01 ATT&CK/S0376 - HOPLIGHT|S0376: HOPLIGHT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HOPLIGHT](https://attack.mitre.org/software/S0376) has multiple C2 channels in place in case one fails.(Citation: US-CERT HOPLIGHT Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1708aa35-a362-429f-be06-82dc106dfeb4`.
