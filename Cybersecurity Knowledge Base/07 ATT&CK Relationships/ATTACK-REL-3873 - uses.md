---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1090"
stix_relationship_id: "relationship--acde21f1-6ece-44c6-89b4-aee4a6cf0ae1"
---
# Relationship 3873: G1052 — uses → T1090

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has leveraged Astrill VPN for C2.(Citation: Recorded Future Contagious Inteview BeaverTail InvisibleFerret OtterCookie February 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--acde21f1-6ece-44c6-89b4-aee4a6cf0ae1`.
