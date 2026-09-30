---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "S0417"
stix_relationship_id: "relationship--08678e7f-c675-4f85-9593-f06cb90f6e44"
---
# Relationship 4863: G0046 — uses → S0417

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0417 - GRIFFON|S0417: GRIFFON]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: SecureList Griffon May 2019)(Citation: CrowdStrike Carbon Spider August 2021)(Citation: FBI Flash FIN7 USB)(Citation: Microsoft Ransomware as a Service)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08678e7f-c675-4f85-9593-f06cb90f6e44`.
