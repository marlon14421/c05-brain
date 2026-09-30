---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0147"
target_object: "T1071.001"
stix_relationship_id: "relationship--50f39180-6e5a-476b-b18f-d4e09e83c9d9"
---
# Relationship 2839: S0147 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0147 - Pteranodon|S0147: Pteranodon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pteranodon](https://attack.mitre.org/software/S0147) can use HTTP for C2.(Citation: Palo Alto Gamaredon Feb 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--50f39180-6e5a-476b-b18f-d4e09e83c9d9`.
