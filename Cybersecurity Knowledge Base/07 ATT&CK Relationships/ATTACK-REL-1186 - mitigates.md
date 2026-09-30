---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1553.005"
stix_relationship_id: "relationship--e6dd2026-0c65-4a42-a306-d525bb442ab3"
---
# Relationship 1186: M1038 — mitigates → T1553.005

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1553.005 - Mark-of-the-Web Bypass|T1553.005: Mark-of-the-Web Bypass]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider blocking container file types at web and/or email gateways. Consider unregistering container file extensions in Windows File Explorer.(Citation: Dormann Dangers of VHD 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6dd2026-0c65-4a42-a306-d525bb442ab3`.
