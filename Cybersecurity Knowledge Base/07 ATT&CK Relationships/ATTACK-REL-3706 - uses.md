---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0668"
target_object: "T1573.002"
stix_relationship_id: "relationship--16d07e92-1026-4d2f-ad4d-a1cb664d1278"
---
# Relationship 3706: S0668 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0668 - TinyTurla|S0668: TinyTurla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TinyTurla](https://attack.mitre.org/software/S0668) has the ability to encrypt C2 traffic with SSL/TLS.(Citation: Talos TinyTurla September 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16d07e92-1026-4d2f-ad4d-a1cb664d1278`.
