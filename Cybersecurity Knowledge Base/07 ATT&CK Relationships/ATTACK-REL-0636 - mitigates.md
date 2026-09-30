---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1542.005"
stix_relationship_id: "relationship--f0488c32-f937-4eb9-8068-092795872582"
---
# Relationship 0636: M1047 — mitigates → T1542.005

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1542.005 - TFTP Boot|T1542.005: TFTP Boot]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Periodically check the integrity of the running configuration and system image to ensure they have not been modified. (Citation: Cisco IOS Software Integrity Assurance - Image File Verification) (Citation: Cisco IOS Software Integrity Assurance - Image File Integrity) (Citation: Cisco IOS Software Integrity Assurance - Change Control)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0488c32-f937-4eb9-8068-092795872582`.
