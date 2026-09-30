---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1052"
target_object: "T1548.002"
stix_relationship_id: "relationship--86eb3c0d-b1c1-4b52-b802-18f321450f29"
---
# Relationship 1146: M1052 — mitigates → T1548.002

**Source object:** [[01 ATT&CK/M1052 - User Account Control|M1052: User Account Control]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1548.002 - Bypass User Account Control|T1548.002: Bypass User Account Control]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Although UAC bypass techniques exist, it is still prudent to use the highest enforcement level for UAC when possible and mitigate bypass opportunities that exist with techniques such as [DLL](https://attack.mitre.org/techniques/T1574/001).

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86eb3c0d-b1c1-4b52-b802-18f321450f29`.
