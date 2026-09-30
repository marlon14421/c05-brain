---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1049"
target_object: "T1080"
stix_relationship_id: "relationship--a2bda2c9-b4cb-4a4c-9fce-f8efbab38fa6"
---
# Relationship 0908: M1049 — mitigates → T1080

**Source object:** [[01 ATT&CK/M1049 - Antivirus-Antimalware|M1049: Antivirus/Antimalware]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1080 - Taint Shared Content|T1080: Taint Shared Content]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Anti-virus can be used to automatically quarantine suspicious files.(Citation: Mandiant Cloudy Logs 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2bda2c9-b4cb-4a4c-9fce-f8efbab38fa6`.
