---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1104"
target_object: "T1556.004"
stix_relationship_id: "relationship--0117960a-178b-41f8-b7c1-5a4852be582a"
---
# Relationship 2804: S1104 — uses → T1556.004

**Source object:** [[01 ATT&CK/S1104 - SLOWPULSE|S1104: SLOWPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1556.004 - Network Device Authentication|T1556.004: Network Device Authentication]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SLOWPULSE](https://attack.mitre.org/software/S1104) can modify LDAP and two factor authentication flows by inspecting login credentials and forcing successful authentication if the provided password matches a chosen backdoor password.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0117960a-178b-41f8-b7c1-5a4852be582a`.
