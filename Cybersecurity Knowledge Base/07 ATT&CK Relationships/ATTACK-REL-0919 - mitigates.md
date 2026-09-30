---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1049"
target_object: "T1027.014"
stix_relationship_id: "relationship--27993745-de4c-4ce0-b27d-cd591b0489c2"
---
# Relationship 0919: M1049 — mitigates → T1027.014

**Source object:** [[01 ATT&CK/M1049 - Antivirus-Antimalware|M1049: Antivirus/Antimalware]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1027.014 - Polymorphic Code|T1027.014: Polymorphic Code]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Anti-virus can be used to automatically detect and quarantine suspicious files. Employment of advanced anti-malware techniques that make use of technologies like machine learning and behavior-based mechanisms to conduct signature-less malware detection will also be more effective than traditional indicator-based detection methods.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--27993745-de4c-4ce0-b27d-cd591b0489c2`.
