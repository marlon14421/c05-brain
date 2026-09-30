---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1049"
target_object: "T1564"
stix_relationship_id: "relationship--a4139ea2-b04d-472a-9daa-0ff3eb5586ce"
---
# Relationship 0267: M1049 — mitigates → T1564

**Source object:** [[01 ATT&CK/M1049 - Antivirus-Antimalware|M1049: Antivirus/Antimalware]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564 - Hide Artifacts|T1564: Hide Artifacts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Review and audit file/folder exclusions, and limit scope of exclusions to only what is required where possible.(Citation: Microsoft File Folder Exclusions)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a4139ea2-b04d-472a-9daa-0ff3eb5586ce`.
