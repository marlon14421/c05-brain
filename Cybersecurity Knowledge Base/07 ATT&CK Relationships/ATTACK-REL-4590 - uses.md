---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1132.001"
stix_relationship_id: "relationship--9e472909-7f89-430f-8782-8bf20ef265d4"
---
# Relationship 4590: S0268 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) has encoded binary data with Base64 and ASCII.(Citation: Kaspersky CactusPete Aug 2020)(Citation: Talos Bisonal Mar 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9e472909-7f89-430f-8782-8bf20ef265d4`.
