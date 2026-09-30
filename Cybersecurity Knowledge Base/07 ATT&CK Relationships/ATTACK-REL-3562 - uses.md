---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0004"
target_object: "T1071.004"
stix_relationship_id: "relationship--96a7d789-70a9-42d8-a78e-b7ffd6c9dc69"
---
# Relationship 3562: G0004 — uses → T1071.004

**Source object:** [[01 ATT&CK/G0004 - Ke3chang|G0004: Ke3chang]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.004 - DNS|T1071.004: DNS]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ke3chang](https://attack.mitre.org/groups/G0004) malware RoyalDNS has used DNS for C2.(Citation: NCC Group APT15 Alive and Strong)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96a7d789-70a9-42d8-a78e-b7ffd6c9dc69`.
