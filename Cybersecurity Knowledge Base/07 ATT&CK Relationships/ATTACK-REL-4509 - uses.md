---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1056"
target_object: "T1176.002"
stix_relationship_id: "relationship--f4b6ec8f-fa03-4584-929b-649ef3e999b1"
---
# Relationship 4509: G1056 — uses → T1176.002

**Source object:** [[01 ATT&CK/G1056 - TeamPCP|G1056: TeamPCP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1176.002 - IDE Extensions|T1176.002: IDE Extensions]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TeamPCP](https://attack.mitre.org/groups/G1056) has compromised VS Code and Open VSX IDE extensions.(Citation: Wiz TeamPCP KICS MAR 2026)(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Trend Micro TeamPCP MAY 2026)(Citation: Phoenix TeamPCP 20 MAY 2026)(Citation: Flashpoint Mini Shai-Hulud MAY 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f4b6ec8f-fa03-4584-929b-649ef3e999b1`.
