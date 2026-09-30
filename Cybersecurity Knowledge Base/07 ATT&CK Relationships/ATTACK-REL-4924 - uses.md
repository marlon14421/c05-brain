---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1073"
target_object: "T1095"
stix_relationship_id: "relationship--d942783e-906f-4d2c-963b-1cc2f8429ff1"
---
# Relationship 4924: S1073 — uses → T1095

**Source object:** [[01 ATT&CK/S1073 - Royal|S1073: Royal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Royal](https://attack.mitre.org/software/S1073) establishes a TCP socket for C2 communication using the API `WSASocketW`.(Citation: Cybereason Royal December 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d942783e-906f-4d2c-963b-1cc2f8429ff1`.
