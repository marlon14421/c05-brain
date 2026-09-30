---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1050"
target_object: "S0183"
stix_relationship_id: "relationship--c77168a4-5298-4f33-9462-008f9487d49c"
---
# Relationship 2664: G1050 — uses → S0183

**Source object:** [[01 ATT&CK/G1050 - Water Galura|G1050: Water Galura]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0183 - Tor|S0183: Tor]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Water Galura](https://attack.mitre.org/groups/G1050) maintains a [Tor](https://attack.mitre.org/software/S0183)-hosted data leaks site for [Qilin](https://attack.mitre.org/software/S1242) ransomware and affiliates.(Citation: BushidoToken Qilin RaaS JUN 2024)(Citation: Sophos Qilin MSP APR 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c77168a4-5298-4f33-9462-008f9487d49c`.
