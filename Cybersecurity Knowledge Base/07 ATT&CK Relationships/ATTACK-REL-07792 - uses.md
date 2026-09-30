---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0024"
target_object: "T1555"
stix_relationship_id: "relationship--d398f48c-9d01-4f6e-bb19-3ebae25cb71c"
---
# Relationship 7792: C0024 — uses → T1555

**Source object:** [[01 ATT&CK/C0024 - SolarWinds Compromise|C0024: SolarWinds Compromise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [SolarWinds Compromise](https://attack.mitre.org/campaigns/C0024), [APT29](https://attack.mitre.org/groups/G0016) used account credentials they obtained to attempt access to Group Managed Service Account (gMSA) passwords.(Citation: Microsoft Deep Dive Solorigate January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d398f48c-9d01-4f6e-bb19-3ebae25cb71c`.
