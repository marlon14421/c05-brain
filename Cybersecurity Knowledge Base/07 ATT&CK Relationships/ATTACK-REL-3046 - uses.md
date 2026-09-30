---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1129"
target_object: "T1083"
stix_relationship_id: "relationship--079b3956-d020-4b9d-a230-e43b391e261f"
---
# Relationship 3046: S1129 — uses → T1083

**Source object:** [[01 ATT&CK/S1129 - Akira|S1129: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Akira](https://attack.mitre.org/software/S1129) examines files prior to encryption to determine if they meet requirements for encryption and can be encrypted by the ransomware. These checks are performed through native Windows functions such as GetFileAttributesW .(Citation: Kersten Akira 2023)(Citation: Cisco Akira Ransomware OCT 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--079b3956-d020-4b9d-a230-e43b391e261f`.
