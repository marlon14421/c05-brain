---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0114"
target_object: "T1071.001"
stix_relationship_id: "relationship--39da4f4e-e382-4db0-8184-cff27532173f"
---
# Relationship 4152: G0114 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0114 - Chimera|G0114: Chimera]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Chimera](https://attack.mitre.org/groups/G0114) has used HTTPS for C2 communications.(Citation: NCC Group Chimera January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39da4f4e-e382-4db0-8184-cff27532173f`.
