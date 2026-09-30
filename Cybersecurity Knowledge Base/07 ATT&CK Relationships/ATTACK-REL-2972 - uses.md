---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0588"
target_object: "T1001.001"
stix_relationship_id: "relationship--a6a4bbf3-7a2e-46ae-877a-614bf9f81644"
---
# Relationship 2972: S0588 — uses → T1001.001

**Source object:** [[01 ATT&CK/S0588 - GoldMax|S0588: GoldMax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GoldMax](https://attack.mitre.org/software/S0588) has used decoy traffic to surround its malicious network traffic to avoid detection.(Citation: MSTIC NOBELIUM Mar 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a6a4bbf3-7a2e-46ae-877a-614bf9f81644`.
