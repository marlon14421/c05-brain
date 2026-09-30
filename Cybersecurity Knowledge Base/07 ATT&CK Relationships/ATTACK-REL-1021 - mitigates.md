---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1024"
target_object: "T1686.003"
stix_relationship_id: "relationship--a58e681b-7b34-426b-ba4f-2983c9de6316"
---
# Relationship 1021: M1024 — mitigates → T1686.003

**Source object:** [[01 ATT&CK/M1024 - Restrict Registry Permissions|M1024: Restrict Registry Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure proper Registry permissions are in place to prevent adversaries from disabling or modifying firewall settings.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a58e681b-7b34-426b-ba4f-2983c9de6316`.
