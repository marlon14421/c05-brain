---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0439"
target_object: "T1569.002"
stix_relationship_id: "relationship--8483ad9a-84c9-4c83-a4d7-d403e44735dc"
---
# Relationship 4718: S0439 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0439 - Okrum|S0439: Okrum]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Okrum](https://attack.mitre.org/software/S0439)'s loader can create a new service named NtmsSvc to execute the payload.(Citation: ESET Okrum July 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8483ad9a-84c9-4c83-a4d7-d403e44735dc`.
