---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0582"
target_object: "T1574.001"
stix_relationship_id: "relationship--fdbb45a4-1151-4c21-909c-1c653c883544"
---
# Relationship 2954: S0582 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0582 - LookBack|S0582: LookBack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LookBack](https://attack.mitre.org/software/S0582) side loads its communications module as a DLL into the libcurl.dll loader.(Citation: Proofpoint LookBack Malware Aug 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fdbb45a4-1151-4c21-909c-1c653c883544`.
