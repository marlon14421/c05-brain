---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0203"
target_object: "T1005"
stix_relationship_id: "relationship--5073b1b4-4018-4208-a46e-86a8358a6cee"
---
# Relationship 3761: S0203 — uses → T1005

**Source object:** [[01 ATT&CK/S0203 - Hydraq|S0203: Hydraq]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Hydraq](https://attack.mitre.org/software/S0203) creates a backdoor through which remote attackers can read data from files.(Citation: Symantec Trojan.Hydraq Jan 2010)(Citation: Symantec Hydraq Jan 2010)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5073b1b4-4018-4208-a46e-86a8358a6cee`.
