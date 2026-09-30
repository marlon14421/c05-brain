---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1198"
target_object: "T1071.001"
stix_relationship_id: "relationship--8a52753e-bd37-4b1f-8886-4b2e474acf1d"
---
# Relationship 3705: S1198 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1198 - Gomir|S1198: Gomir]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Gomir](https://attack.mitre.org/software/S1198) periodically communicates to its command and control infrastructure through HTTP POST requests.(Citation: Symantec Troll Stealer 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8a52753e-bd37-4b1f-8886-4b2e474acf1d`.
