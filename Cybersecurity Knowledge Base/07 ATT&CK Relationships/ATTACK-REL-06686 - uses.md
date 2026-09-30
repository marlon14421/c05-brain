---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1006"
target_object: "T1588.001"
stix_relationship_id: "relationship--e607a77e-5c5c-4f3e-a62d-82124a434911"
---
# Relationship 6686: G1006 — uses → T1588.001

**Source object:** [[01 ATT&CK/G1006 - Earth Lusca|G1006: Earth Lusca]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.001 - Malware|T1588.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Earth Lusca](https://attack.mitre.org/groups/G1006) has acquired and used a variety of malware, including [Cobalt Strike](https://attack.mitre.org/software/S0154).(Citation: TrendMicro EarthLusca 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e607a77e-5c5c-4f3e-a62d-82124a434911`.
