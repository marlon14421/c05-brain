---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0091"
target_object: "T1553.002"
stix_relationship_id: "relationship--908f1fa6-c797-47c3-bcb1-3438a9105095"
---
# Relationship 7318: G0091 — uses → T1553.002

**Source object:** [[01 ATT&CK/G0091 - Silence|G0091: Silence]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Silence](https://attack.mitre.org/groups/G0091) has used a valid certificate to sign their primary loader Silence.Downloader (aka TrueBot).(Citation: Group IB Silence Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--908f1fa6-c797-47c3-bcb1-3438a9105095`.
