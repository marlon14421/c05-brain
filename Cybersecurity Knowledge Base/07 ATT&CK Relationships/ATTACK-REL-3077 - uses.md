---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0158"
target_object: "T1095"
stix_relationship_id: "relationship--fce7fac2-91da-4903-95dc-fb54650c0859"
---
# Relationship 3077: S0158 — uses → T1095

**Source object:** [[01 ATT&CK/S0158 - PHOREAL|S0158: PHOREAL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PHOREAL](https://attack.mitre.org/software/S0158) communicates via ICMP for C2.(Citation: FireEye APT32 May 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fce7fac2-91da-4903-95dc-fb54650c0859`.
