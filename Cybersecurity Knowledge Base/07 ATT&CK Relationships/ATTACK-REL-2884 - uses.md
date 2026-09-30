---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1219.002"
stix_relationship_id: "relationship--87e0b924-d2a6-4e65-95ed-9500670bbe5c"
---
# Relationship 2884: G1015 — uses → T1219.002

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219.002 - Remote Desktop Software|T1219.002: Remote Desktop Software]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

In addition to directing victims to run remote software, [Scattered Spider](https://attack.mitre.org/groups/G1015) members themselves also deploy RMM software including TeamViewer, AnyDesk, LogMeIn, [ngrok](https://attack.mitre.org/software/S0508), and [ConnectWise](https://attack.mitre.org/software/S0591) to establish persistence on the compromised network.(Citation: CISA Scattered Spider Advisory November 2023)(Citation: Trellix Scattered Spider MO August 2023)(Citation: Mandiant UNC3944 May 2025)(Citation: CrowdStrike Scattered Spider JUL 2025)(Citation: Check Point Scattered Spider JUL 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--87e0b924-d2a6-4e65-95ed-9500670bbe5c`.
