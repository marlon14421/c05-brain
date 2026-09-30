---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1070"
target_object: "T1553.002"
stix_relationship_id: "relationship--26e2d87c-43c2-4552-9186-2ca0f70e96c7"
---
# Relationship 2975: S1070 — uses → T1553.002

**Source object:** [[01 ATT&CK/S1070 - Black Basta|S1070: Black Basta]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [Black Basta](https://attack.mitre.org/software/S1070) dropper has been digitally signed with a certificate issued by Akeo Consulting for legitimate executables used for creating bootable USB drives.(Citation: Check Point Black Basta October 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26e2d87c-43c2-4552-9186-2ca0f70e96c7`.
