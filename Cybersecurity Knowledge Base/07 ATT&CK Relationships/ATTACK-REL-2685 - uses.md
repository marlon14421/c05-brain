---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0659"
target_object: "T1071.001"
stix_relationship_id: "relationship--2f3389a4-e0a6-4dc5-b5ff-38fd185e2821"
---
# Relationship 2685: S0659 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0659 - Diavol|S0659: Diavol]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Diavol](https://attack.mitre.org/software/S0659) has used HTTP GET and POST requests for C2.(Citation: Fortinet Diavol July 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2f3389a4-e0a6-4dc5-b5ff-38fd185e2821`.
