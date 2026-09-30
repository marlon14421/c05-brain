---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1568"
stix_relationship_id: "relationship--d7647e3e-d554-44e0-97e0-b8d5abab3cab"
---
# Relationship 4210: G0099 — uses → T1568

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has used DDNS services such as DuckDNS, noip[.]com, and con-ip[.]com to redirect victims to sites or repositories hosting malware implants.(Citation: Kaspersky BlindEagle AUG 2024)(Citation: Check Point Blind Eagle MAR 2025)(Citation: LevelBlue Blind Eagle Proton66 JUN 2025)(Citation: Recorded Future TAG-144 AUG 2025)(Citation: Zscaler BlindEagle DEC 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d7647e3e-d554-44e0-97e0-b8d5abab3cab`.
