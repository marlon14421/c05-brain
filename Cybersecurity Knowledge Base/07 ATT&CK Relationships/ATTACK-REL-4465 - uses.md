---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0680"
target_object: "T1113"
stix_relationship_id: "relationship--516fd2f8-a709-43f4-86e1-c753e28113e1"
---
# Relationship 4465: S0680 — uses → T1113

**Source object:** [[01 ATT&CK/S0680 - LitePower|S0680: LitePower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LitePower](https://attack.mitre.org/software/S0680) can take system screenshots and save them to `%AppData%`.(Citation: Kaspersky WIRTE November 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--516fd2f8-a709-43f4-86e1-c753e28113e1`.
