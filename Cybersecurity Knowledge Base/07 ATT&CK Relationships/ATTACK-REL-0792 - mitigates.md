---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1046"
target_object: "T1195.003"
stix_relationship_id: "relationship--6800b404-bdfe-46bf-8ce3-54819f990e1f"
---
# Relationship 0792: M1046 — mitigates → T1195.003

**Source object:** [[01 ATT&CK/M1046 - Boot Integrity|M1046: Boot Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1195.003 - Compromise Hardware Supply Chain|T1195.003: Compromise Hardware Supply Chain]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Use Trusted Platform Module technology and a secure or trusted boot process to prevent system integrity from being compromised. Check the integrity of the existing BIOS or EFI to determine if it is vulnerable to modification.(Citation: TCG Trusted Platform Module)(Citation: TechNet Secure Boot Process)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6800b404-bdfe-46bf-8ce3-54819f990e1f`.
