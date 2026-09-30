---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0334"
target_object: "T1057"
stix_relationship_id: "relationship--7c60bccc-f485-403d-ab3b-db861a3a4429"
---
# Relationship 4476: S0334 — uses → T1057

**Source object:** [[01 ATT&CK/S0334 - DarkComet|S0334: DarkComet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkComet](https://attack.mitre.org/software/S0334) can list active processes running on the victim’s machine.(Citation: Malwarebytes DarkComet March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c60bccc-f485-403d-ab3b-db861a3a4429`.
