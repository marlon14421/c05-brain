---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0593"
target_object: "T1074.001"
stix_relationship_id: "relationship--f8c1f1e4-4580-4ec6-9bc0-6f24214dc273"
---
# Relationship 2977: S0593 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0593 - ECCENTRICBANDWAGON|S0593: ECCENTRICBANDWAGON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ECCENTRICBANDWAGON](https://attack.mitre.org/software/S0593) has stored keystrokes and screenshots within the %temp%\GoogleChrome , %temp%\Downloads , and %temp%\TrendMicroUpdate directories.(Citation: CISA EB Aug 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f8c1f1e4-4580-4ec6-9bc0-6f24214dc273`.
