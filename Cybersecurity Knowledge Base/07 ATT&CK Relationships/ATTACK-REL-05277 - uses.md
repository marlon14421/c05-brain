---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1018"
stix_relationship_id: "relationship--7748c6c9-d7a5-44e9-81bf-97d038e6edb1"
---
# Relationship 5277: C0024 — uses → T1018

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) used [AdFind](https://attack.mitre.org/software/S0552) to enumerate remote systems.(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7748c6c9-d7a5-44e9-81bf-97d038e6edb1`.
