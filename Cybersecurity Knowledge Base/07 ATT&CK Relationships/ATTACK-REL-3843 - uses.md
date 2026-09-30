---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0053"
target_object: "T1133"
stix_relationship_id: "relationship--9abd0448-a3b7-4262-8753-fe81dc91c434"
---
# Relationship 3843: G0053 — uses → T1133

**Source object:** [[01 ATT&CK/G0053 - FIN5|G0053: FIN5]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN5](https://attack.mitre.org/groups/G0053) has used legitimate VPN, Citrix, or VNC credentials to maintain access to a victim environment.(Citation: FireEye Respond Webinar July 2017)(Citation: DarkReading FireEye FIN5 Oct 2015)(Citation: Mandiant FIN5 GrrCON Oct 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9abd0448-a3b7-4262-8753-fe81dc91c434`.
