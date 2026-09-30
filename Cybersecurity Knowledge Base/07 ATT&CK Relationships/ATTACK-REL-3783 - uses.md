---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0375"
target_object: "T1113"
stix_relationship_id: "relationship--d5b4ef43-ddb4-4f95-95b9-6a352700bb77"
---
# Relationship 3783: S0375 — uses → T1113

**Source object:** [[01 ATT&CK/S0375 - Remexi|S0375: Remexi]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Remexi](https://attack.mitre.org/software/S0375) takes screenshots of windows of interest.(Citation: Securelist Remexi Jan 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5b4ef43-ddb4-4f95-95b9-6a352700bb77`.
