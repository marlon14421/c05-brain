---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1021"
target_object: "T1566"
stix_relationship_id: "relationship--a205b0ce-df00-40ae-b626-7dc3e8146d45"
---
# Relationship 0129: M1021 — mitigates → T1566

**Source object:** [[01 ATT&CK/M1021 - Restrict Web-Based Content|M1021: Restrict Web-Based Content]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1566 - Phishing|T1566: Phishing]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Determine if certain websites or attachment types (ex: .scr, .exe, .pif, .cpl, etc.) that can be used for phishing are necessary for business operations and consider blocking access if activity cannot be monitored well or if it poses a significant risk.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a205b0ce-df00-40ae-b626-7dc3e8146d45`.
