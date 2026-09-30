---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1049"
target_object: "T1027"
stix_relationship_id: "relationship--ffa8f46b-615f-4b95-8ed5-90f86eaedd20"
---
# Relationship 0968: M1049 — mitigates → T1027

**Source object:** [[01 ATT&CK/M1049 - Antivirus-Antimalware|M1049: Antivirus/Antimalware]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Anti-virus can be used to automatically detect and quarantine suspicious files. Consider utilizing the Antimalware Scan Interface (AMSI) on Windows 10+ to analyze commands after being processed/interpreted. (Citation: Microsoft AMSI June 2015)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffa8f46b-615f-4b95-8ed5-90f86eaedd20`.
