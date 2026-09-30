---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0083"
target_object: "T1070.009"
stix_relationship_id: "relationship--81d62795-b28f-4146-b4ff-b74da5cf514b"
---
# Relationship 3475: S0083 — uses → T1070.009

**Source object:** [[01 ATT&CK/S0083 - Misdat|S0083: Misdat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.009 - Clear Persistence|T1070.009: Clear Persistence]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Misdat](https://attack.mitre.org/software/S0083) is capable of deleting Registry keys used for persistence.(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81d62795-b28f-4146-b4ff-b74da5cf514b`.
