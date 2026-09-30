---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0583"
target_object: "T1046"
stix_relationship_id: "relationship--fefae8e3-2549-4743-9713-7dfa40c52ae4"
---
# Relationship 4183: S0583 — uses → T1046

**Source object:** [[01 ATT&CK/S0583 - Pysa|S0583: Pysa]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pysa](https://attack.mitre.org/software/S0583) can perform network reconnaissance using the Advanced Port Scanner tool.(Citation: CERT-FR PYSA April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fefae8e3-2549-4743-9713-7dfa40c52ae4`.
