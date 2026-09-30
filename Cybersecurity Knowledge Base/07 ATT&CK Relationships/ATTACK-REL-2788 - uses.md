---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0368"
target_object: "T1047"
stix_relationship_id: "relationship--76eae7b3-2e02-41c6-8b31-b81c8d124006"
---
# Relationship 2788: S0368 — uses → T1047

**Source object:** [[01 ATT&CK/S0368 - NotPetya|S0368: NotPetya]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NotPetya](https://attack.mitre.org/software/S0368) can use wmic to help propagate itself across a network.(Citation: Talos Nyetya June 2017)(Citation: US-CERT NotPetya 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--76eae7b3-2e02-41c6-8b31-b81c8d124006`.
