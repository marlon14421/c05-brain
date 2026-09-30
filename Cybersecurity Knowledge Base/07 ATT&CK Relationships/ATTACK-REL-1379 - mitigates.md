---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1040"
target_object: "T1486"
stix_relationship_id: "relationship--9c8dee77-e751-40b6-ab99-ccfe6a832e0a"
---
# Relationship 1379: M1040 — mitigates → T1486

**Source object:** [[01 ATT&CK/M1040 - Behavior Prevention on Endpoint|M1040: Behavior Prevention on Endpoint]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

On Windows 10, enable cloud-delivered protection and Attack Surface Reduction (ASR) rules to block the execution of files that resemble ransomware.(Citation: win10_asr) In AWS environments, create an IAM policy to restrict or block the use of SSE-C on S3 buckets.(Citation: Halcyon AWS Ransomware 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c8dee77-e751-40b6-ab99-ccfe6a832e0a`.
