---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0043"
target_object: "S0596"
stix_relationship_id: "relationship--631ea273-6871-47fb-96ef-8fb4a3826c14"
---
# Relationship 6076: C0043 — uses → S0596

**Source object:** [[01 ATT&CK/C0043 - Indian Critical Infrastructure Intrusions|C0043: Indian Critical Infrastructure Intrusions]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0596 - ShadowPad|S0596: ShadowPad]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Indian Critical Infrastructure Intrusions](https://attack.mitre.org/campaigns/C0043) included the use of [ShadowPad](https://attack.mitre.org/software/S0596) malware for operations.(Citation: RecordedFuture RedEcho 2022)(Citation: Dragos YIR 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--631ea273-6871-47fb-96ef-8fb4a3826c14`.
