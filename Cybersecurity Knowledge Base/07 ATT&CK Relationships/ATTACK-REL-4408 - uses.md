---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0011"
target_object: "T1005"
stix_relationship_id: "relationship--6b9cb729-6a81-4ec2-91c1-7141f8691ee4"
---
# Relationship 4408: S0011 — uses → T1005

**Source object:** [[01 ATT&CK/S0011 - Taidoor|S0011: Taidoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Taidoor](https://attack.mitre.org/software/S0011) can upload data and files from a victim's machine.(Citation: TrendMicro Taidoor)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6b9cb729-6a81-4ec2-91c1-7141f8691ee4`.
