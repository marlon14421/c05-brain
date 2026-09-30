---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0428"
target_object: "T1048.003"
stix_relationship_id: "relationship--613ba18d-d23b-443a-9e1a-c2d564132fe2"
---
# Relationship 3693: S0428 — uses → T1048.003

**Source object:** [[01 ATT&CK/S0428 - PoetRAT|S0428: PoetRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PoetRAT](https://attack.mitre.org/software/S0428) has used [ftp](https://attack.mitre.org/software/S0095) for exfiltration.(Citation: Talos PoetRAT April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--613ba18d-d23b-443a-9e1a-c2d564132fe2`.
