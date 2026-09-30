---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0513"
target_object: "T1012"
stix_relationship_id: "relationship--59c92aeb-1e62-4e60-8ead-63100e068c0d"
---
# Relationship 3978: S0513 — uses → T1012

**Source object:** [[01 ATT&CK/S0513 - LiteDuke|S0513: LiteDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LiteDuke](https://attack.mitre.org/software/S0513) can query the Registry to check for the presence of HKCU\Software\KasperskyLab .(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59c92aeb-1e62-4e60-8ead-63100e068c0d`.
