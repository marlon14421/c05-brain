---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1045"
target_object: "T1601.002"
stix_relationship_id: "relationship--775f9337-6cab-49f6-850e-af3038f0c806"
---
# Relationship 0500: M1045 — mitigates → T1601.002

**Source object:** [[01 ATT&CK/M1045 - Code Signing|M1045: Code Signing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1601.002 - Downgrade System Image|T1601.002: Downgrade System Image]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Many vendors provide digitally signed operating system images to validate the integrity of the software used on their platform. Make use of this feature where possible in order to prevent and/or detect attempts by adversaries to compromise the system image. (Citation: Cisco IOS Software Integrity Assurance - Deploy Signed IOS)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--775f9337-6cab-49f6-850e-af3038f0c806`.
