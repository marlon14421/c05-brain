---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1003.006"
stix_relationship_id: "relationship--c34b776e-2fca-4ff9-910d-486bf9447d78"
---
# Relationship 6985: C0024 — uses → T1003.006

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.006 - DCSync|T1003.006: DCSync]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) used privileged accounts to replicate directory service data with domain controllers.(Citation: Microsoft 365 Defender Solorigate)(Citation: Microsoft Deep Dive Solorigate January 2021)(Citation: CrowdStrike StellarParticle January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c34b776e-2fca-4ff9-910d-486bf9447d78`.
