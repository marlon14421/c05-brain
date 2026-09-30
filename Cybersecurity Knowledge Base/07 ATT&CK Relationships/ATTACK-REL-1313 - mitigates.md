---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1050"
target_object: "T1210"
stix_relationship_id: "relationship--2627d84f-081d-4b14-9d7d-5a1ca77d5869"
---
# Relationship 1313: M1050 — mitigates → T1210

**Source object:** [[01 ATT&CK/M1050 - Exploit Protection|M1050: Exploit Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Security applications that look for behavior used during exploitation such as Windows Defender Exploit Guard (WDEG) and the Enhanced Mitigation Experience Toolkit (EMET) can be used to mitigate some exploitation behavior. (Citation: TechNet Moving Beyond EMET) Control flow integrity checking is another way to potentially identify and stop a software exploit from occurring. (Citation: Wikipedia Control Flow Integrity) Many of these protections depend on the architecture and target application binary for compatibility and may not work for all software or services targeted.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2627d84f-081d-4b14-9d7d-5a1ca77d5869`.
