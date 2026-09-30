---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9015"
target_object: "T1036.005"
stix_relationship_id: "relationship--25fe3382-4792-4fa7-b439-2249bf572e72"
---
# Relationship 2995: S9015 — uses → T1036.005

**Source object:** [[01 ATT&CK/S9015 - BRICKSTORM|S9015: BRICKSTORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BRICKSTORM](https://attack.mitre.org/software/S9015) has appeared to resemble legitimate processes to include the vCenter process `vami-http`.(Citation: CrowdStrike BRICKSTORM WARP PANDA UNC5221 December 2025)(Citation: Google UNC5221 BRICKSTORM SPAWNCHIMERA April 2024)(Citation: Google BRICKSTORM September 2025) [BRICKSTORM](https://attack.mitre.org/software/S9015) has also leveraged legitimate names of VMware vSphere platform such as `vmsrc` or `vmware-sphere`.(Citation: CISA BRICKSTORM UNC5221 AR25-338A February 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25fe3382-4792-4fa7-b439-2249bf572e72`.
