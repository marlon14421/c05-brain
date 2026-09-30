---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1156"
target_object: "T1132.001"
stix_relationship_id: "relationship--b6714e64-3741-4d0a-9377-6aa743cda936"
---
# Relationship 4011: S1156 — uses → T1132.001

**Source object:** [[01 ATT&CK/S1156 - Manjusaka|S1156: Manjusaka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Manjusaka](https://attack.mitre.org/software/S1156) communication includes a client-created session cookie with base64-encoded information representing information from the victim system.(Citation: Talos Manjusaka 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6714e64-3741-4d0a-9377-6aa743cda936`.
