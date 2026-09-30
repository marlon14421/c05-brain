---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0468"
target_object: "T1140"
stix_relationship_id: "relationship--952412b3-a7b1-402c-a92e-96830df4d14b"
---
# Relationship 3018: S0468 — uses → T1140

**Source object:** [[01 ATT&CK/S0468 - Skidmap|S0468: Skidmap]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Skidmap](https://attack.mitre.org/software/S0468) has the ability to download, unpack, and decrypt tar.gz files .(Citation: Trend Micro Skidmap)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--952412b3-a7b1-402c-a92e-96830df4d14b`.
