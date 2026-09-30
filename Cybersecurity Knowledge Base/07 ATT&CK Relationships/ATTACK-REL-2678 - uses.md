---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9044"
target_object: "T1564.008"
stix_relationship_id: "relationship--9b5f7f79-bed4-49c0-b251-7ec6731b0f95"
---
# Relationship 2678: S9044 — uses → T1564.008

**Source object:** [[01 ATT&CK/S9044 - Kali365|S9044: Kali365]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.008 - Email Hiding Rules|T1564.008: Email Hiding Rules]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kali365](https://attack.mitre.org/software/S9044) has the ability to modify email rules to delete email based notifications prior to the victim seeing them.(Citation: SpyCloud Kali365 June 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b5f7f79-bed4-49c0-b251-7ec6731b0f95`.
