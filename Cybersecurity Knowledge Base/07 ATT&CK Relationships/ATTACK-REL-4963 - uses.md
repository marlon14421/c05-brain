---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1180"
target_object: "T1021.002"
stix_relationship_id: "relationship--dc2077f1-b891-48f8-a1a0-397ed8601bde"
---
# Relationship 4963: S1180 — uses → T1021.002

**Source object:** [[01 ATT&CK/S1180 - BlackByte Ransomware|S1180: BlackByte Ransomware]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BlackByte Ransomware](https://attack.mitre.org/software/S1180) uses mapped shared folders to transfer ransomware payloads via SMB.(Citation: Trustwave BlackByte 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc2077f1-b891-48f8-a1a0-397ed8601bde`.
