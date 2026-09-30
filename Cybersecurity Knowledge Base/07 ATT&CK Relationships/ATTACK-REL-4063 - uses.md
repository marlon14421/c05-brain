---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0001"
target_object: "T1190"
stix_relationship_id: "relationship--e11a3d87-d9cf-4dcf-b722-fef4b0a324b4"
---
# Relationship 4063: G0001 — uses → T1190

**Source object:** [[01 ATT&CK/G0001 - Axiom|G0001: Axiom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Axiom](https://attack.mitre.org/groups/G0001) has been observed using SQL injection to gain access to systems.(Citation: Novetta-Axiom)(Citation: Cisco Group 72)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e11a3d87-d9cf-4dcf-b722-fef4b0a324b4`.
