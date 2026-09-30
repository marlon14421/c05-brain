---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1593.003"
stix_relationship_id: "relationship--84606e1e-f445-48b9-b6be-f9ad6ddafc99"
---
# Relationship 4138: S9008 — uses → T1593.003

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1593.003 - Code Repositories|T1593.003: Code Repositories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has the ability to search open sites and code repositories for compromised credentials.(Citation: Aikido Shai-Hulud September 2025)(Citation: Microsoft Shai-Hulud December 2025) [Shai-Hulud](https://attack.mitre.org/software/S9008) has discovered packages associated with compromised accounts.(Citation: Netskope Shai-Hulud November 2025) [Shai-Hulud](https://attack.mitre.org/software/S9008) has also searched code repositories for other compromised repositories that include predefined parameters or markers to include “Second Coming” combined with an 18-character alphanumeric string.(Citation: Netskope Shai-Hulud November 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--84606e1e-f445-48b9-b6be-f9ad6ddafc99`.
