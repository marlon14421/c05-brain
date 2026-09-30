---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1036.012"
stix_relationship_id: "relationship--964b451b-103a-4bef-9a1f-a2078cd81cf9"
---
# Relationship 0376: M1047 — mitigates → T1036.012

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1036.012 - Browser Fingerprint|T1036.012: Browser Fingerprint]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Review and limit the fingerprinting surface to only necessary information on each browser to make the browser less unique. For example, the available fonts may be limited to a standard font list. (Citation: W3C)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--964b451b-103a-4bef-9a1f-a2078cd81cf9`.
