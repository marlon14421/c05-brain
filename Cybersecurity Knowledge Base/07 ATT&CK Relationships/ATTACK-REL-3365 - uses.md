---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0530"
target_object: "T1566.002"
stix_relationship_id: "relationship--e6c6afdc-a52f-405c-8480-a4b2d2d797bf"
---
# Relationship 3365: S0530 — uses → T1566.002

**Source object:** [[01 ATT&CK/S0530 - Melcoz|S0530: Melcoz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Melcoz](https://attack.mitre.org/software/S0530) has been spread through malicious links embedded in e-mails.(Citation: Securelist Brazilian Banking Malware July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e6c6afdc-a52f-405c-8480-a4b2d2d797bf`.
