---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1099"
target_object: "T1573.001"
stix_relationship_id: "relationship--7943f92f-8956-4bb9-9f92-c932fb267b19"
---
# Relationship 4118: S1099 — uses → T1573.001

**Source object:** [[01 ATT&CK/S1099 - Samurai|S1099: Samurai]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Samurai](https://attack.mitre.org/software/S1099) can encrypt C2 communications with AES.(Citation: Kaspersky ToddyCat June 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7943f92f-8956-4bb9-9f92-c932fb267b19`.
