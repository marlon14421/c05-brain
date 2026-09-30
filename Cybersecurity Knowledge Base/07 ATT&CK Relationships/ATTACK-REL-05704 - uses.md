---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0377"
target_object: "T1008"
stix_relationship_id: "relationship--36849ab3-088c-47a5-bcf9-3e68902a2e60"
---
# Relationship 5704: S0377 — uses → T1008

**Source object:** [[01 ATT&CK/S0377 - Ebury|S0377: Ebury]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1008 - Fallback Channels|T1008: Fallback Channels]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ebury](https://attack.mitre.org/software/S0377) has implemented a fallback mechanism to begin using a DGA when the attacker hasn't connected to the infected system for three days.(Citation: ESET Ebury Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36849ab3-088c-47a5-bcf9-3e68902a2e60`.
