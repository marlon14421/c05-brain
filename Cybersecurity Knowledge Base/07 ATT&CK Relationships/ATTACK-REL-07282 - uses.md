---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0040"
target_object: "S1158"
stix_relationship_id: "relationship--8acce9df-baaa-4495-b273-ca925ea68ad8"
---
# Relationship 7282: C0040 — uses → S1158

**Source object:** [[01 ATT&CK/C0040 - APT41 DUST|C0040: APT41 DUST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S1158 - DUSTPAN|S1158: DUSTPAN]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DUSTPAN](https://attack.mitre.org/software/S1158) was used during [APT41 DUST](https://attack.mitre.org/campaigns/C0040).(Citation: Google Cloud APT41 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8acce9df-baaa-4495-b273-ca925ea68ad8`.
