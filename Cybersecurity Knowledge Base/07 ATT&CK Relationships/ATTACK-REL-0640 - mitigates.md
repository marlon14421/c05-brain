---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1027"
target_object: "T1555.003"
stix_relationship_id: "relationship--d2bb226a-810d-47ea-be8d-397b9dd94031"
---
# Relationship 0640: M1027 — mitigates → T1555.003

**Source object:** [[01 ATT&CK/M1027 - Password Policies|M1027: Password Policies]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Organizations may consider weighing the risk of storing credentials in web browsers. If web browser credential disclosure is a significant concern, technical controls, policy, and user training may be used to prevent storage of credentials in web browsers.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2bb226a-810d-47ea-be8d-397b9dd94031`.
