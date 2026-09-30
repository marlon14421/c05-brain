---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0086"
target_object: "T1105"
stix_relationship_id: "relationship--2025480a-6d91-4ef5-a6ea-cc025c8aecfb"
---
# Relationship 4751: S0086 — uses → T1105

**Source object:** [[01 ATT&CK/S0086 - ZLib|S0086: ZLib]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZLib](https://attack.mitre.org/software/S0086) has the ability to download files.(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2025480a-6d91-4ef5-a6ea-cc025c8aecfb`.
