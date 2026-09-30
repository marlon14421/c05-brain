---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0230"
target_object: "T1574.001"
stix_relationship_id: "relationship--4a4664c1-47dd-4a4a-ab7b-0f64ec137a67"
---
# Relationship 4628: S0230 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0230 - ZeroT|S0230: ZeroT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZeroT](https://attack.mitre.org/software/S0230) has used DLL side-loading to load malicious payloads.(Citation: Proofpoint TA459 April 2017)(Citation: Proofpoint ZeroT Feb 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a4664c1-47dd-4a4a-ab7b-0f64ec137a67`.
