---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0051"
target_object: "T1071.001"
stix_relationship_id: "relationship--d9e8d70a-06f6-4873-baf8-29ebfaf6bf99"
---
# Relationship 3194: S0051 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0051 - MiniDuke|S0051: MiniDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[MiniDuke](https://attack.mitre.org/software/S0051) uses HTTP and HTTPS for command and control.(Citation: F-Secure The Dukes)(Citation: ESET Dukes October 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9e8d70a-06f6-4873-baf8-29ebfaf6bf99`.
