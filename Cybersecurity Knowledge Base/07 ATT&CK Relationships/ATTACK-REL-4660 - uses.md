---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0381"
target_object: "T1033"
stix_relationship_id: "relationship--2b8418de-6474-49e2-84f0-01ffe6c07a42"
---
# Relationship 4660: S0381 — uses → T1033

**Source object:** [[01 ATT&CK/S0381 - FlawedAmmyy|S0381: FlawedAmmyy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FlawedAmmyy](https://attack.mitre.org/software/S0381) enumerates the current user during the initial infection.(Citation: Proofpoint TA505 Mar 2018)(Citation: Korean FSI TA505 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b8418de-6474-49e2-84f0-01ffe6c07a42`.
