---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1057"
target_object: "T1583.001"
stix_relationship_id: "relationship--df55f1d1-f7a0-4e93-af6a-ee4e47d0b809"
---
# Relationship 3690: G1057 — uses → T1583.001

**Source object:** [[01 ATT&CK/G1057 - ShinyHunters|G1057: ShinyHunters]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ShinyHunters](https://attack.mitre.org/groups/G1057) has established clearnet and Tor data leak sites (DLS) including one named “SHINYHUNTERS” for the exfiltration and posting of stolen data.(Citation: Mandiant_SHDataTheft_Jan2026)(Citation: FBI_SHLMS_May2026) Additionally, [ShinyHunters](https://attack.mitre.org/groups/G1057) has registered domains that mimic legitimate Microsoft Azure NetApp Files endpoints, such as azurenetfiles[.]net, and legitimate Okta SSO login pages, such as trial-6857053.okta[.]com.(Citation: Google_SHOracle_Jun2026)(Citation: ElecticIQ Buyukkaya_ShinyHunters_Sept2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--df55f1d1-f7a0-4e93-af6a-ee4e47d0b809`.
