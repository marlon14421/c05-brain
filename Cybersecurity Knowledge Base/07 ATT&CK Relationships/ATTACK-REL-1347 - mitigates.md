---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1535"
stix_relationship_id: "relationship--70add783-c72c-4048-ba94-5e1e79c2d679"
---
# Relationship 1347: M1054 — mitigates → T1535

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1535 - Unused-Unsupported Cloud Regions|T1535: Unused/Unsupported Cloud Regions]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Cloud service providers may allow customers to deactivate unused regions.(Citation: CloudSploit - Unused AWS Regions)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70add783-c72c-4048-ba94-5e1e79c2d679`.
