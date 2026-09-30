---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1550.001"
stix_relationship_id: "relationship--eb204b76-676b-48c2-a6e4-d773eef16bdc"
---
# Relationship 4926: S9008 — uses → T1550.001

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1550.001 - Application Access Token|T1550.001: Application Access Token]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has leveraged captured valid NPM tokens to enumerate and update packages on compromised accounts.(Citation: Aikido Shai-Hulud September 2025)(Citation: Socket Shai-Hulud November 2025)(Citation: Socket Shai-Hulud Trufflehog September 2025) [Shai-Hulud](https://attack.mitre.org/software/S9008) has also utilized stolen GitHub access tokens to access compromised accounts.(Citation: Socket Shai-Hulud November 2025)(Citation: Socket Shai-Hulud Trufflehog September 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb204b76-676b-48c2-a6e4-d773eef16bdc`.
