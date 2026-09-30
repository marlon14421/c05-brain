---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1043"
target_object: "T1558.005"
stix_relationship_id: "relationship--a1530db3-cb4d-4645-abfa-b669b33340ee"
---
# Relationship 0726: M1043 — mitigates → T1558.005

**Source object:** [[01 ATT&CK/M1043 - Credential Access Protection|M1043: Credential Access Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1558.005 - Ccache Files|T1558.005: Ccache Files]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Protect resources with Security Enhanced Linux (SELinux) by defining entry points, process types, and file labels.(Citation: Brining MimiKatz to Unix)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1530db3-cb4d-4645-abfa-b669b33340ee`.
