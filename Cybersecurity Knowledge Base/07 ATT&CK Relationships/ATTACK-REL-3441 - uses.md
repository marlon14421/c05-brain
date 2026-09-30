---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "S0039"
stix_relationship_id: "relationship--d64f970a-8003-41bf-9769-d849c12340ed"
---
# Relationship 3441: G0102 — uses → S0039

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

(Citation: CrowdStrike Ryuk January 2019)(Citation: Red Canary Hospital Thwarted Ryuk October 2020)(Citation: FireEye KEGTAP SINGLEMALT October 2020)(Citation: DFIR Ryuk's Return October 2020)(Citation: DFIR Ryuk 2 Hour Speed Run November 2020)(Citation: DFIR Ryuk in 5 Hours October 2020)(Citation: Sophos New Ryuk Attack October 2020)(Citation: Mandiant FIN12 Oct 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d64f970a-8003-41bf-9769-d849c12340ed`.
