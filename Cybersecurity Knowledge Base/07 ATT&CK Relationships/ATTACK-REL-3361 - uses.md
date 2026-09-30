---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0134"
target_object: "T1584.001"
stix_relationship_id: "relationship--2a27a98e-ee19-49f3-96e4-a5c9ee6e65ed"
---
# Relationship 3361: G0134 — uses → T1584.001

**Source object:** [[01 ATT&CK/G0134 - Transparent Tribe|G0134: Transparent Tribe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.001 - Domains|T1584.001: Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Transparent Tribe](https://attack.mitre.org/groups/G0134) has compromised domains for use in targeted malicious campaigns.(Citation: Proofpoint Operation Transparent Tribe March 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2a27a98e-ee19-49f3-96e4-a5c9ee6e65ed`.
