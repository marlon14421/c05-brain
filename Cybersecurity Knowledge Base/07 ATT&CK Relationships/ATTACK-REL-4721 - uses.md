---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0147"
target_object: "T1083"
stix_relationship_id: "relationship--5d46a519-1ef9-4cdb-b737-8c7b3ffb4f0e"
---
# Relationship 4721: S0147 — uses → T1083

**Source object:** [[01 ATT&CK/S0147 - Pteranodon|S0147: Pteranodon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pteranodon](https://attack.mitre.org/software/S0147) identifies files matching certain file extension and copies them to subdirectories it created.(Citation: Palo Alto Gamaredon Feb 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5d46a519-1ef9-4cdb-b737-8c7b3ffb4f0e`.
