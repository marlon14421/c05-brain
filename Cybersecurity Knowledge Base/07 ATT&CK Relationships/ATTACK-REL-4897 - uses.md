---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1021.002"
stix_relationship_id: "relationship--b5f6b196-576d-4f4e-be05-1923cbbd21a0"
---
# Relationship 4897: C0029 — uses → T1021.002

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors moved laterally using compromised credentials to connect to internal Windows systems with SMB.(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5f6b196-576d-4f4e-be05-1923cbbd21a0`.
