---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1530"
stix_relationship_id: "relationship--e3e50d39-fa69-4fca-9353-259247dbd439"
---
# Relationship 0170: M1047 — mitigates → T1530

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1530 - Data from Cloud Storage|T1530: Data from Cloud Storage]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Frequently check permissions on cloud storage to ensure proper permissions are set to deny open or unprivileged access to resources.(Citation: Amazon S3 Security, 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3e50d39-fa69-4fca-9353-259247dbd439`.
