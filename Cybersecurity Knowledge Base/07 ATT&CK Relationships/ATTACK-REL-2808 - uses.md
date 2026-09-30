---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0084"
target_object: "T1016"
stix_relationship_id: "relationship--39e856a1-4bab-474e-a6b2-3ce69249bc29"
---
# Relationship 2808: S0084 — uses → T1016

**Source object:** [[01 ATT&CK/S0084 - Mis-Type|S0084: Mis-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Mis-Type](https://attack.mitre.org/software/S0084) may create a file containing the results of the command cmd.exe /c ipconfig /all .(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39e856a1-4bab-474e-a6b2-3ce69249bc29`.
