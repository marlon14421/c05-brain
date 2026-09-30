---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0059"
target_object: "T1090.003"
stix_relationship_id: "relationship--74ca2dd6-3194-42f3-bee6-6a9a59b082ab"
---
# Relationship 4072: C0059 — uses → T1090.003

**Source object:** [[01 ATT&CK/C0059 - Salesforce Data Exfiltration|C0059: Salesforce Data Exfiltration]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059), threat actors used [Tor](https://attack.mitre.org/software/S0183) IPs for voice calls and for the collection of stolen data.(Citation: Google Salesforce JUN 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74ca2dd6-3194-42f3-bee6-6a9a59b082ab`.
