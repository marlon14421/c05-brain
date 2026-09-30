---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1045"
target_object: "T1525"
stix_relationship_id: "relationship--24e20a3c-5f74-40bc-a5b0-108bc0233305"
---
# Relationship 0862: M1045 — mitigates → T1525

**Source object:** [[01 ATT&CK/M1045 - Code Signing|M1045: Code Signing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1525 - Implant Internal Image|T1525: Implant Internal Image]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Several cloud service providers support content trust models that require container images be signed by trusted sources.(Citation: Content trust in Azure Container Registry)(Citation: Content trust in Docker)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--24e20a3c-5f74-40bc-a5b0-108bc0233305`.
