---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0346"
target_object: "T1566.001"
stix_relationship_id: "relationship--faf1e821-465d-40cc-b523-73f1ba308932"
---
# Relationship 2736: S0346 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0346 - OceanSalt|S0346: OceanSalt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OceanSalt](https://attack.mitre.org/software/S0346) has been delivered via spearphishing emails with Microsoft Office attachments.(Citation: McAfee Oceansalt Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--faf1e821-465d-40cc-b523-73f1ba308932`.
