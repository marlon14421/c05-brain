---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1195.002"
stix_relationship_id: "relationship--dba2e83b-a79b-4d4e-8c32-70b7c8f2491f"
---
# Relationship 6448: C0024 — uses → T1195.002

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1195.002 - Compromise Software Supply Chain|T1195.002: Compromise Software Supply Chain]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) gained initial network access to some victims via a trojanized update of SolarWinds Orion software.(Citation: SolarWinds Sunburst Sunspot Update January 2021)(Citation: FireEye SUNBURST Backdoor December 2020)(Citation: Cybersecurity Advisory SVR TTP May 2021)(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dba2e83b-a79b-4d4e-8c32-70b7c8f2491f`.
