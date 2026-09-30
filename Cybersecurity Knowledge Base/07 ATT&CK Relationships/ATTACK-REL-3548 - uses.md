---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1227"
target_object: "T1573.001"
stix_relationship_id: "relationship--0618bd56-0ca0-4750-ac4e-ab6fa475298c"
---
# Relationship 3548: S1227 — uses → T1573.001

**Source object:** [[01 ATT&CK/S1227 - StarProxy|S1227: StarProxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[StarProxy](https://attack.mitre.org/software/S1227) has leveraged two 256-byte XOR keys to encrypt and decrypt network packets using a custom algorithm.(Citation: Zscaler)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0618bd56-0ca0-4750-ac4e-ab6fa475298c`.
