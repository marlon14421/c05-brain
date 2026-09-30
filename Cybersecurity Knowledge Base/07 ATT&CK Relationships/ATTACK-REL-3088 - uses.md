---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0142"
target_object: "T1071.001"
stix_relationship_id: "relationship--a68cb676-409e-483d-8af1-500d57ad1f81"
---
# Relationship 3088: G0142 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0142 - Confucius|G0142: Confucius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Confucius](https://attack.mitre.org/groups/G0142) has used HTTP for C2 communications.(Citation: Uptycs Confucius APT Jan 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a68cb676-409e-483d-8af1-500d57ad1f81`.
