---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1020"
target_object: "T1105"
stix_relationship_id: "relationship--eeebf544-5120-400b-9e79-d98aa070f905"
---
# Relationship 4555: G1020 — uses → T1105

**Source object:** [[01 ATT&CK/G1020 - Mustard Tempest|G1020: Mustard Tempest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mustard Tempest](https://attack.mitre.org/groups/G1020) has deployed secondary payloads and third stage implants to compromised hosts.(Citation: Microsoft Ransomware as a Service)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eeebf544-5120-400b-9e79-d98aa070f905`.
