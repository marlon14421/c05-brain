---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0049"
target_object: "T1018"
stix_relationship_id: "relationship--52ec8e9e-4276-4793-bc9b-76c312cba5cd"
---
# Relationship 6253: C0049 — uses → T1018

**Source object:** [[01 ATT&CK/C0049 - Leviathan Australian Intrusions|C0049: Leviathan Australian Intrusions]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) performed extensive remote host enumeration to build their own map of victim networks during [Leviathan Australian Intrusions](https://attack.mitre.org/campaigns/C0049).(Citation: CISA Leviathan 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52ec8e9e-4276-4793-bc9b-76c312cba5cd`.
