---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0247"
target_object: "T1059.003"
stix_relationship_id: "relationship--a2440552-4190-4f72-9cf5-a63eecdff2fb"
---
# Relationship 3584: S0247 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0247 - NavRAT|S0247: NavRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[NavRAT](https://attack.mitre.org/software/S0247) leverages cmd.exe to perform discovery techniques.(Citation: Talos NavRAT May 2018) [NavRAT](https://attack.mitre.org/software/S0247) loads malicious shellcode and executes it in memory.(Citation: Talos NavRAT May 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a2440552-4190-4f72-9cf5-a63eecdff2fb`.
