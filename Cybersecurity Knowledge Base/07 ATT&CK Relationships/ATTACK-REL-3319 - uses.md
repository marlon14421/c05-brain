---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0538"
target_object: "T1567.002"
stix_relationship_id: "relationship--6193189a-f24c-4680-9a20-d191f42b9c97"
---
# Relationship 3319: S0538 — uses → T1567.002

**Source object:** [[01 ATT&CK/S0538 - Crutch|S0538: Crutch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1567.002 - Exfiltration to Cloud Storage|T1567.002: Exfiltration to Cloud Storage]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Crutch](https://attack.mitre.org/software/S0538) has exfiltrated stolen data to Dropbox.(Citation: ESET Crutch December 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6193189a-f24c-4680-9a20-d191f42b9c97`.
