---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0697"
target_object: "T1553.002"
stix_relationship_id: "relationship--415f38f8-d490-461a-9a40-968f8cd2bd8b"
---
# Relationship 3697: S0697 — uses → T1553.002

**Source object:** [[01 ATT&CK/S0697 - HermeticWiper|S0697: HermeticWiper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [HermeticWiper](https://attack.mitre.org/software/S0697) executable has been signed with a legitimate certificate issued to Hermetica Digital Ltd.(Citation: Symantec Ukraine Wipers February 2022)(Citation: Crowdstrike DriveSlayer February 2022)(Citation: ESET Hermetic Wiper February 2022)(Citation: Qualys Hermetic Wiper March 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--415f38f8-d490-461a-9a40-968f8cd2bd8b`.
