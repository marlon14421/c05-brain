---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0194"
target_object: "T1027.005"
stix_relationship_id: "relationship--26eca19b-1c55-49b5-8a07-a4131c577874"
---
# Relationship 7840: S0194 — uses → T1027.005

**Source object:** [[01 ATT&CK/S0194 - PowerSploit|S0194: PowerSploit]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.005 - Indicator Removal from Tools|T1027.005: Indicator Removal from Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerSploit](https://attack.mitre.org/software/S0194)'s Find-AVSignature AntivirusBypass module can be used to locate single byte anti-virus signatures.(Citation: GitHub PowerSploit May 2012)(Citation: PowerSploit Documentation)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26eca19b-1c55-49b5-8a07-a4131c577874`.
