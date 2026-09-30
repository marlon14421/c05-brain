---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9007"
target_object: "T1071.001"
stix_relationship_id: "relationship--94a02780-a86d-45f0-a1c4-2b7864879dcf"
---
# Relationship 4194: S9007 — uses → T1071.001

**Source object:** [[01 ATT&CK/S9007 - HTTPTroy|S9007: HTTPTroy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HTTPTroy](https://attack.mitre.org/software/S9007) has used HTTP POST requests to communicate with C2.(Citation: Gen Digital Kimsuky HTTPTroy October 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--94a02780-a86d-45f0-a1c4-2b7864879dcf`.
