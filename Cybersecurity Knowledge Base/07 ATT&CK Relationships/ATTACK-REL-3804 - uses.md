---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9041"
target_object: "T1546.016"
stix_relationship_id: "relationship--5eb8c9b7-a1c0-4d70-a84c-a9ff50253ed1"
---
# Relationship 3804: S9041 — uses → T1546.016

**Source object:** [[01 ATT&CK/S9041 - TeamPCP Cloud Stealer|S9041: TeamPCP Cloud Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1546.016 - Installer Packages|T1546.016: Installer Packages]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamPCP Cloud Stealer](https://attack.mitre.org/software/S9041) can inject malicious pre or post-install scripts within package.json for payload execution.(Citation: Palo Alto TeamPCP MAR 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5eb8c9b7-a1c0-4d70-a84c-a9ff50253ed1`.
