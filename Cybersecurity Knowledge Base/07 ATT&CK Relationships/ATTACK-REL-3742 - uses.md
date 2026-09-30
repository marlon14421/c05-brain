---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0125"
target_object: "T1567.002"
stix_relationship_id: "relationship--80efda4a-36a7-4b59-9f70-72f4952e2140"
---
# Relationship 3742: G0125 — uses → T1567.002

**Source object:** [[01 ATT&CK/G0125 - HAFNIUM|G0125: HAFNIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HAFNIUM](https://attack.mitre.org/groups/G0125) has exfiltrated data to file sharing sites, including MEGA.(Citation: Microsoft HAFNIUM March 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80efda4a-36a7-4b59-9f70-72f4952e2140`.
