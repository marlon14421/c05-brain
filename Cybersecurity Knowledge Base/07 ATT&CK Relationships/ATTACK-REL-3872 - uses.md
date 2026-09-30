---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0046"
target_object: "T1587.003"
stix_relationship_id: "relationship--403c4fd2-5d87-4dfd-8fcf-e7abdbbb8a87"
---
# Relationship 3872: C0046 — uses → T1587.003

**Source object:** [[01 ATT&CK/C0046 - ArcaneDoor|C0046: ArcaneDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.003 - Digital Certificates|T1587.003: Digital Certificates]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ArcaneDoor](https://attack.mitre.org/campaigns/C0046) included acquiring digital certificates mimicking patterns associated with Cisco ASA appliances for command and control infrastructure.(Citation: Cisco ArcaneDoor 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--403c4fd2-5d87-4dfd-8fcf-e7abdbbb8a87`.
