---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0412"
target_object: "T1056.001"
stix_relationship_id: "relationship--f0a91093-3827-49b0-82c4-a1c882f074cf"
---
# Relationship 3463: S0412 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0412 - ZxShell|S0412: ZxShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZxShell](https://attack.mitre.org/software/S0412) has a feature to capture a remote computer's keystrokes using a keylogger.(Citation: FireEye APT41 Aug 2019)(Citation: Talos ZxShell Oct 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0a91093-3827-49b0-82c4-a1c882f074cf`.
