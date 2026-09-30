---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1690"
stix_relationship_id: "relationship--49d7f44b-7b35-4b86-8930-2e6bb644776a"
---
# Relationship 4100: G1041 — uses → T1690

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1690 - Prevent Command History Logging|T1690: Prevent Command History Logging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) unset the Bash and MySQL history files on victim systems.(Citation: Hunt Sea Turtle 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--49d7f44b-7b35-4b86-8930-2e6bb644776a`.
